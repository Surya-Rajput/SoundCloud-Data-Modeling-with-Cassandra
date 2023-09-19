# SoundCloud-Data-Modeling-with-Cassandra

# SoundCloud Data Modeling with Cassandra

This repository contains the code and data modeling for a music streaming app, SoundCloud, using Cassandra. The aim of this project is to create a NoSQL database to help SoundCloud analyze user activity and song data more efficiently.

## Introduction

SoundCloud is a music streaming app that has been collecting data on songs and user activity. Currently, the data is stored in CSV files, making it challenging to query and analyze effectively. The objective of this project is to create a NoSQL database using Cassandra to address this challenge and facilitate data analysis.

## List of Queries

### Query 1
**Find the artist_name, song_title, and length of the song from the SoundCloud app history that was heard during session_number = 338 and item_in_session_number = 4.**

### Query 2
**Find the artist_name, song_title (sorted by item_in_session_number), and name (first name and last name) of the user for user_id = 10 and session_number = 182.**

### Query 3
**Find every name (first name and last name) of the user from the SoundCloud app history that listened to the song_title 'All Hands Against His Own'.**
