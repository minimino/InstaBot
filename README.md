# InstaBot
We needed a cheap way to gather users related to other users from Instagram. This bot does exactly that: given an initual username, it connects to Instagram APIs and gathers related users.

# How

When fetching Instagram's APIs, there's a field in the JSON response that returns related users. For each of these users, we get their related users. This way we can get an infinite number of users potentially related to the first one.
