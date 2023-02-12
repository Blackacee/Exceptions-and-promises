# Exceptions-and-promises

Promise.resolve(5)
 .then(result => {
 throw new Error("I don't like five");
 })
 .then(result => {
 console.info("Promise resolved: " + result);
 })
 .catch(error => {
 console.error("Promise rejected: " + error);
 });
