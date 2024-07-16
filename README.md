<?php

/*$foods1=array("apple", "banana", "charry");


print_r($foods1 [2]);*/

/*$app = ['Android','ISO','Windows','Linux'];
foreach ($app as $item){

    echo $item. "<br/>";
}

$fruits = ['apple', 'banana', 'Orange', 'Charry'];
foreach ($fruits as $item){
    echo $item. "<br/>";
}*/

/*$bilgates=[
    "fristname"=> "bill",
    "lastname"=>"gates",
    "age"=> "65",
    "gender"=> "male",
    "email"=> "bilgates@gmail.com",
    "phonenumber"=> "123456789" 
];
foreach($bilgates as $key=>$value){
    echo $key.":".$value."<br/>";
}*/

$fruits1 = ['apple1', 'banana1', 'Orange1', 'Charry1'];
$fruits2 = ['apple2', 'banana2', 'Orange2', 'Charry2'];
$fruits3 = ['apple3', 'banana3', 'Orange3', 'Charry3'];
$fruits4 = ['apple4', 'banana4', 'Orange4', 'Charry4'];
$fruits5 = ['apple5', 'banana5', 'Orange5', 'Charry5'];

      $All_fruits=[$fruits1, $fruits2, $fruits3, $fruits4, $fruits5];

      foreach ($All_fruits as $parentfourts) {
        foreach ($parentfourts as $childfourts){
        echo $childfourts. "<br/>";
      }
    }

    
