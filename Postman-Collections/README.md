//Automated Assertions Example:
pm.test ("Status code is 200", function () {
pm.response.to. have. Status (200);
});

pm.test ("Response time is acceptable", function () {
pm. expect (pm. response. response Time). to.be. below (1500);
});
