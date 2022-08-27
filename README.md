# MusicBiz

## ASP.NET MVC Music application

This app is a music app where depending on your role, you are given certain assessability.
Ablbums, Artists and Tracks are all connected with relationships

## Entity Models: 
- Album
- Artist
- Genre
- RoleClaim
- Track

## Roles:
Executive: can add Artists, Album for an artist and Tracks to an Album.
Coordinator: can add Album for an artist and Tracks.
Clerk: can add Tracks to an Album.
Staff/Logged out: can log and view the Genre, Artists, Albumbs and Tracks

## Accounts:
- Executive - executive@example.com
- Coordinator - coord@example.com
- Clerk - clerk@example.com
- Staff - staff@example.com
- Password - Password123!

## Load Data
- RoleClaims - /loaddata
- Genre - /loadgenre
- Artists - /loadartists
- Albums - /loadAlbums

## Remove Data
- Remove all data - /loaddata/Remove
- Remove Database - /removedatabase
