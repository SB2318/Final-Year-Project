# Final Year Project

post recipe json format:
{
"RECIPE_TITLE": "Jalapeno Popper Grilled Cheese Sandwich",
"IMAGE_URL": "https://bing.com/th?id=OSK.602054f41f7ba09555a9fa6f16cf42da",
"RECIPE_PUBLISHER": "xyzjyfuy",
"SOURCE_URL": "http://www.closetcooking.com/2011/04/jalapeno-popper-grilled-cheese-sandwich.html",
"PUBLISHED_DATE": "2023-04-03"
}


## CREATE TABLE:

CREATE TABLE `ahesadb`.`recipe_table` (`ID` VARCHAR(50) NOT NULL , `RECIPE_TITLE` VARCHAR(30) NOT NULL , `IMAGE_URL` VARCHAR(200) NOT NULL , `TIME_TAKEN` VARCHAR(20) NOT NULL , `RECIPE_PUBLISHER` VARCHAR(30) NOT NULL , `SOURCE_URL` VARCHAR(200) NOT NULL , `PUBLISHED_DATE` VARCHAR(30) NOT NULL )

## INSERT INFO:

INSERT INTO `recipe_table` (`ID`, `RECIPE_TITLE`, `IMAGE_URL`, `TIME_TAKEN`, `RECIPE_PUBLISHER`, `SOURCE_URL`, `PUBLISHED_DATE`) VALUES ('1234561', 'Eggless Chocolate Cake', 'https://www.vegrecipesofindia.com/wp-content/uploads/2021/04/eggless-chocolate-cake-1.jpg', '45', 'Dassana Amit', 'https://www.vegrecipesofindia.com/basic-eggless-chocolate-cake-recipe/', 'February 7, 2023');
