# Api
The server api is using the AspNetCoreRateLimit library which store the api resquests for each client in memory.
The current configuration is to allow 2 requests for each client per minute.
Once the limit is reached the api will return an error with a HttpStatusCode of 429 to the client.
