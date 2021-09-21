# DiscordWH_FreeGames
r/GameDealsFree Webhook format for Discord servers, for use in applications, IFTTT, etc.

This is a simple repo holding the Webhook JSON format for use by IFTTT and other applications to use with r/GameDeals and r/GameDealsFree to push to a specific channel using services like IFTTT or other similar services, or your own software.

As of now, the file WebhookTry4.json seems to work, and WebhookTry4_Test2_Working.json does indeed work if you use Postman to make a POST web request with the JSON format (select raw, then on the right hand side, select JSON), and in the request address, simply put in your Discord Webhook URL to test it. It'll push an example. The WebhookTry4.json file is set up specifically for use with IFTTT with a Reddit RSS search result as the trigger, and a webhook as the action.
