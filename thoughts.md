# Data

## Authenticate
- Waitlist
- Signup
- Login

## Users

- ID
- Name
- Email 
- Picture
- Signup date
- Current location
- Last location and time
- Scrawls

## Locations
- ID
- location ID (Foursqure or other ID) 
- Lat, Long, Altitude, 
- Type
    Sphere: Raidius
    Box:
- Name
- Scrawls


## Scrawl
- ID
- User ID
- Datetime
- Text
- Referenced media
- Status (live, deleted, etc)
- Rating
- Comments/responses
   - ID
   - user ID
   - Text
       - Referenced media

## Media
- Images
- Audio
- Video


# Interactions

## Views

### Mapbox (or google) map view
- View based on current location
- Map pins of current scrawls, perhaps some location name displays?
- Scrawl here (on current location)
    - Authoring interface
    - Anonymous?
- Select pin
    - Read existing scrawls
    - Respond or thumb up (or down?) existing scrawl
    - Search for scrawls?
    
## Notifications
- Push - You are near a scrawl
- Someone has commented on your scrawl.
- New scrawls near your scrawl
 
    
# Misc

Places APIs:

- Google 
- Foursquare
- Yelp, Yext, Facebook

