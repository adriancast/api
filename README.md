# Fake API server to build dummy clients
This fake API returns static data. The routes available are:
- https://raw.githubusercontent.com/adriancast/api/main/bookings
- https://raw.githubusercontent.com/adriancast/api/main/clients
- https://raw.githubusercontent.com/adriancast/api/main/hotels


Happy hacking !

# Exercises

Build a API using your tool of choice. You should create the following routes:
- Given a client ID, return the hotel tags that match their taste. For example, if Carlos booked a hotel that is "adults" category and another hotel that is "beach" category, the endpoint should return that for Carlos their tags are "beach" and "adults"

- Given a hotel_id and a year, return the clients that did a booking.

- Given a tag, return all the hotel that has that category. For example, all hotels that have "adults" category.

- Given a tag, return all the users that did a booking in a hotel with that tag.
