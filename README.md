# Baidu Aip 

> Give the Aip namespace in PHP 7.0+  
Forked from Linij/BaiduAip

## Features

- PHP7.0 + 
- Namespace
- Package Management By Composer

## Log
- 2020.04.26 Updated Baidu Aip version 2_2_19

## Installation

`composer require mrlongmoon/baiduaip`

## Usage

```php
 $ocr = new AipOcr($appId, $apiKey, $secretKey);
 $ocr->receipt(file_get_contents($imagePath));
```
