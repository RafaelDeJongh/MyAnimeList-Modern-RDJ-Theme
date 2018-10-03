![Description](http://files.gamebanana.com/bitpit/description_e1c38.png)

This is a minimalistic flat designed List Style which focuses around showing the Anime's cover in a nice grid like structure, to be used on the website: MyAnimeList.net with the new Modern List style. 

You can find the original Classic Theme here: https://github.com/RafaelDeJongh/MyAnimeList-Classic-RDJ-Theme

Live Example: [myanimelist.net/animelist/RafaelDeJongh](https://myanimelist.net/animelist/RafaelDeJongh)

![Preview](http://files.gamebanana.com/bitpit/preview_67ec1.png)

![AnimeListPreview](https://files.gamebanana.com/bitpit/modern-mal-rdj-theme.jpg)

![Features](http://files.gamebanana.com/bitpit/features_38a9e.png)

This list style offer various features:

- Fully responsive layout, works on desktop and mobile seamlessly 
- Flat, metro like design for an easy overview
- Full Header Image
- Low Res covers by using the new modern list style

![Installation](http://files.gamebanana.com/bitpit/installation_b6439.png)

For this theme you will need to select the Modern list style type, you can then either choose the default theme OR the Dark Red theme. Make sure you first configure your list settings before continuing editing the theme.

### This list is developed with the following List Settings:

- Numbers
- Score
- Type
- Episodes
- Rating
- Chapters
- Volumes
- Start/End Dates
- Image

After the list settings have been set, you can now add the following code to the "Add Custom CSS" section of the theme itself. 

### The code used for both the Anime & Manga List:

<pre>
/*Designed by Rafael De Jongh*/
@\import "https://malscraper.azurewebsites.net/covers/anime/YOURUSERNAME/presets/dataimagelinkafter";
@\import "https://malscraper.azurewebsites.net/covers/manga/YOURUSERNAME/presets/dataimagelinkafter";
@\import "//rafaeldejongh.github.io/MyAnimeList-Modern-RDJ-Theme/MAL-RDJ-Theme.css";
License{/*Profile Liststyle created for MyAnimeList.com by Rafael De Jongh - https://github.com/RafaelDeJongh//MyAnimeList-Modern-RDJ-Theme*/}
</pre>

**Make sure to change the "YOURUSERNAME" part from the malscraper @import so the covers will be generated for your profile personally, do note that your profile has to be public to be scrapable. If the scraper does not work you can use the pre-generated anime/manga covers from the "cover" folder instead.**

***Because MAL currently disabled @imports, we bypass this by escaping it with a backslash. In case this does not work then copy the whole contents from [the main CSS file here](https://rafaeldejongh.github.io/MyAnimeList-Modern-RDJ-Theme/MAL-RDJ-Theme.css) and paste it into the Custom CSS Section.***

### Changing the Theme color:

This modern edition of the theme comes with Variable CSS Colors, and while this theme is originally build after my personal corporate identity which still is used as a fallback for unsupportive browsers of CSS Variables, you now can alter most of the colors from this theme!

You can do this by altering the color values in the :root{}. Shown below are the default colors which are set for the theme by default:

<pre>
:root{
	--main-theme-color:#900;
	--main-theme-hover-color:#b30000;
	--main-background-color:#17171a;
	--main-background-color-dark:#17171b;
	--scrollbar-background-color:#121212;
	--sec-background-color:#1a1a1a;
	--title-background-color:#242425;
	--title-sec-background-color:#232322;
	--container-background-color:#222;
	--container-background-sec-color:#333;
	--main-transparent-background:rgba(0,0,0,.5);
	--hover-transparent-background:rgba(0,0,0,.3);
	--text-color:#eee;
	--text-color-hover:#fff;
	--status-button-color:#bbb;
	--status-button-color-sec:#666;
	--status-completed-color:1E88E5;
	--status-watching-color:#4CAF50;
	--status-onhold-color:#FFC107;
}
</pre>

All these colors can be adjusted to your own liking, just make sure that you put the edited root code **AFTER** the "License" part to avoid conflicts, and so that it can be properly overwritten without the need of !importants.

I hope you like this addition so you can alter the color set to your own personal liking without going too deep into the code!

### If there are any bugs feel free to let me know!

- You can open up an Issue here on Github
- Contact me on my MyAnimeList Profile
- Contact me on info@rafaeldejongh.com
