# restaurant-reviews
Using this tutorial:
https://www.youtube.com/watch?v=mrHNSanmqQ4&t=1902s


# Troubleshooting Logs
- had to instal Node.js first (google it)

- emm 20:34 (no arquivo index.js) foi necessária alterar algumas properties que estava deprecated:
	- maxPoolSize: 50, 
        - wtimeoutMS: 2500,
        - useNewUrlParser: true}

- ERR_MODULE_NOT_FOUND: provavél erro de digitação

- SERVER TIMEOUT: 
	- My IP has changed. Added authorizathion for the new one

- Web Address:
	- At the office I've been using: localhost:5000/api/v1/restaurants 
	- But at home it looked more like my IP. It was probably because of the extension Cris asked me to install.

- instalei JSON formatter pra conseguir enxergar o JSON melhor
	- https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa/related


- instalei Insomnia
	- https://insomnia.rest/download

- INSOMNIA: SyntaxError: Unexpected token } in JSON at position 109
	- found out that my JSON POST can NOT end with a comma (,)
	- position 109 does NOT mean line. 

# STOPPED AT:
- 


