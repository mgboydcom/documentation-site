+++
title = "Hotel Content"
pagetitle = "Hotel Content (Static Content)"
description = "Learn about how manage content data to manage in your site. Hotel, Boards, Categories..."
weight = 5
alwaysopen = false
+++

On this page you will learn how to manage content data in your site such as hotel, boards, categories, etc.

## Hotels

Hotels query returns a hotel list of the one supplier access. This entity contains static data about the hotel like code, name, location, information about the hotel information, etc... You can find all fields in the [graph](https://api.travelgatex.com/). You can get the hotels with hotel codes or with minimal destination codes. Also you can filter the result with the rank.

### Playground Samples

* [hotels](https://graphqlbin.com/58y0Sp) 

## Hotels Ranking

Hotel Content operations allow changes to be made to static methods on HotelX. A system where hotels can be divided into different rankings or priorities in order to facilitate the mapping process.

The main goal of this process is to create a hotel ranking and divide the whole portfolio so the hotel list is more manageable. Each classification or sub-list responds to specific commercial criteria, such as, the hotels directly contracted, the best offers, the best sales hotels, etc.

Once the hotel ranking file(s) have been uploaded, the static hotel list method can filter hotels according to this ranking. To set up hotel ranking lists you must upload a file in csv format using a specific name to identify the ranking in your organisation’s FTP.

### File Names (mandatory)

Each file can have different meanings. It’s up to the file creator to give it a meaning according to his/her business needs. In order to process files correctly, they must be named according to the following naming convention:

|File Nane| Description|
|---------|------------|
|rank1.csv | Rank 1, for example direct contracts |
|rank2.csv | Rank 2, for example best deals |
|rank3.csv | Rank 3, for example top sales |
|rank4.csv | Rank 4, for example competitive hotels |
|rankN.csv | Rank N, any type of information.|

### Header fields (mandatory)

In order to be correctly processed, the header fields must have the following format:

| Field Name | Data Type |
|-------------|----------|
| provider_id | string |
| hotel_code | string |
| rank | boolean [1,0] |

### Example:

| provider_id | hotel_code |rank |
|-------------|------------|-----|
| travelgatex | 2018 | 1 |
| travelgatey | 2017 | 1 |

### Process file

To process the file, it must be uploaded to your organization’s FTP folder in the TravelgateX Platform. More info on how to upload files please refer to the [data automation section](/travelgatex/data-automation/).

### Template File

For your convinience you can [download a template CSV file](/content/rank1.csv).

## Destinations

Destination query returns a list of static data about destinations for a supplier access. By default if you don’t set the destination codes are all the codes. Like than hotels you can get the other pages with the continuation token.

### Playground Samples

* [destinations](https://graphqlbin.com/763zsZ) 

## Boards

Board static data returns a simple map of the boards that can be returned with its translation to other languages.

### Playground Samples

* [boards](https://graphqlbin.com/6687tV) 

## Rooms

Room static data returns a simple map of the rooms that can be returned with its translation to other languages.

### Playground Samples

* [rooms](https://graphqlbin.com/98rmiY) 

## Categories

Category static data returns a simple map of the categories that can be returned with its translation to other languages.

### Playground Samples

* [categories](https://graphqlbin.com/mwZjT6) 
