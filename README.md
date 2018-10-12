# Chombies
We built this Twitch-integrated Zombies vs Chat overlay live on Twitch!

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you too all the participants of this project!

**Instafluff, Instafriend, RebelRoxie, MacabreMan2, That_MS_Gamer, sethorizer, Replemish, Chibigirl24, samchitto, DEAD_P1XL, raleenakaos, zivivi1, pinkbubbles6789, nightsilas, reverandsaul, jellydance, Infanate_Reapage, joaquimley, KitAnnLIVE, AntiViGames, wietlol, DvDty, koralina_211, NiteCrawla, Lichsmash, SoG_Cuicui, SimmeringSoupPot, Docpinecone, Amarogine, Bjwhite211, Sir_Dave, SuperChihuahua, JokO__, Numb3rY, bloom_molly, Kyoslilmonster, neniltheelf, nallaj, Chlapicek99, sparky_pugwash, CrimsonKnightZero, kitsunechimsa, TentaclePentacle, LuckyPheathers, malfunct, Stay_Hydrated_Bot, Fooberticus, Pixelgourmet, iAmNotFromHere, LakeDK, FablesGames, Neo_TA, Yonlionz, GarethHubball, donaldwm, guthron, asarigreenfire, EchoTheSpaceHippie, cottonsmiles, nelmejor, FuriousFur, ShadowNeverSeen, JoeShimHae**

## Instructions ##

1. Install NodeJS - [https://nodejs.org/en/](https://nodejs.org/en/)
2. Open the directory in a Command Prompt/Terminal
3. Install Dependencies: `npm install`
4. Get a Twitch Chat OAuth Password Token - [http://twitchapps.com/tmi/](http://twitchapps.com/tmi/)
4. Create a file named `.env` that looks like this:
```javascript
PORT=8000
TWITCHUSER=[YOUR-USERNAME-HERE]
OAUTH=[YOUR-OAUTH-PASS HERE] # e.g. OAUTH=oauth:kjh12bn1hsj78445234
```
5. Run Server: `npm start`
6. View the webpage from your web browser! [http://localhost:8000](http://localhost:8000)
