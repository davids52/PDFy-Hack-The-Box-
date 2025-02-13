1. Create file payload.php
2. Hosting a php server locally by this command:

  🔴🔴🔴Note: You must put payload.php in the same path where you run this command.

  ```php -S [IP address for local access or you can type `localhost` only]:[port]```
  
  Ex: ```php -S localhost:6969```

3. Forward web server from local to public:

  ```ssh -R [listening port]:[The IP address that you chose in 2.]:[forwarding port] nokey@[The IP address that you chose in 2.].run```

  Ex: ```ssh -R 80:localhost:6969 nokey@localhost.run```

4. Try to access the URL generated in Step 3 and URL/payload.php , if it doesn't work please check the Note in Step 2
5. Copy the URL/payload.php to challenge, hit the submit button and get the Flag 🏁🏁🏁

Hope you also succeed!!!
