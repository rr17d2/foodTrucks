# foodTruck
This is a food truck locator application in java created in Android Studio.
Within the folder (foodTruck) you will see all the files require to run this application in Android Studio.
- In the application there is 2 options: find food truck and change food truck's location.
- First option: find a food truck. All food trucks are listed in a PHP file --->
   url = getString(R.string.baseUrl) + "truckDesc.php?name=" + URLEncoder.encode(truckName, "UTF-8");
- Second option: update a food truck's location. In times a food truck might change its location and everyone will not know.
    Users have access to change the location of a particular truck. (Assuming everyone is a good samaritan)
