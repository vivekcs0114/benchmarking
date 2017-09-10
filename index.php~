<?php

$host = "localhost";
$port = 3306;
$userName = "root";
$password = '';
$dbName = "pms";
$conn = mysqli_connect($host, $userName, $password, $dbName) or die('echo "Connection Error";');
if (!$conn) {
    die('Could not connect: ' . mysqli_error());
}

$sql = "INSERT INTO user (name, email, mobile, address)
VALUES ('John', 'Doe', 'john@example.com','889897856')";

if (mysqli_query($conn, $sql)) {
    echo "New record created successfully";
} else {
    echo "Error: " . $sql . "<br>" . mysqli_error($conn);
}

mysqli_close($conn);
?>
