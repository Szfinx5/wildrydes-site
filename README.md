# API Routes    

| Method | Path | Role | Expected props | Response |
|---|---|---|---|--|
| GET	| /location/'id' | List all the favourite location of the user | {params: userId} | {success: boolean, payload: [{placeid, latitude , longitude, name, picture }]} | 
| POST | /location | Post a new favourite location for the user | {userId, latitude , longitude, locationName, locationImage }	| {success: boolean, payload: string} |
| DELETE | /location/'id' |	Delete the selected location from favourites | params: {locationId }	| {success: boolean, payload: string}	|
