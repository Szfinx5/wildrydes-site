# API Routes

| Method | Path | Role | Expected props | Response |
|---|---|---|---|--|
| GET	| /location/'id' | List all the favourite location of the user | {params: userId} | {success: boolean, payload: [{locationId, latitude , longitude, name, picture }]} | 
| POST | /location | Post a new favourite location for the user | {locationId, userId, latitude , longitude, locationName, locationImage }	| {success: boolean, payload: string} |
| DELETE | /location/'id' |	Delete the selected location from favourites | params: {locationId }	| {success: boolean, payload: string}	|
