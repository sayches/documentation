## Sayches Public API
Last update: 30/11/2021
 
Warning: Your API key enables access to your account. Keep your API key private. If you believe your API key has been compromised, select the Rotate API Key button on this screen.
The Sayches REST API allow you to build your own customised Sayches clients. The following guide will walk you through the minimum viable Sayches API integration for a seamless Sayches experience. If you have any questions, email us at support@sayches.com.

*Tip: Get your API Key from Settings > Developer > Authorisation Token. If your email is not verified, you won't be able to see the Developer section.*

**Authorisation**
With authentication, permissions determine whether a request should be granted or denied access.

**Header:** ``Authorization: Token <your_api_key>``

**Endpoints:** ``GET /api/post/``

**Example Request:** ``curl --request GET --location 'https://sayches.com/api/post/' \
--header 'Authorization: Token <your_api_key>'``

