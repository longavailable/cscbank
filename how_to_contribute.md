# How to contribute
## 1. Mail [me](mailto:liuxiaolong125@gmail.com)
Just send me a Google Maps link. I will add it when I am free.
## 2. Contribute to this project
- Create a country folder, add it to [readme.md](readme.md), and create a ```<country>_index.md``` file in the country folder.
- Create a city folder, add it to the ```<country>_index.md```, and create a ```<city>_index.md``` file in the city folder.
- Create a landmark or CBD/BC ```html``` file, add it to the ```<city>_index.md``` file, and edit it as follows.
Supposing the html was copied from template.
	- Notice the comment line ```<!-- Name of landmark or CBD/BC -->```, and replace ```De Hoven``` with your place in ```h2``` tag.
	- Notice the comment line ```<!-- Lontitude,latitude and zoom level of landmark or CBD/BC -->```, and replace them with yours.
	- Add your place to Google Maps.
		- Click the editable [link](		https://drive.google.com/open?id=1EXIq_76pPad6DefALKFKps2CDxNLRJi5&usp=sharing) directly, or copy the address ```https://drive.google.com/open?id=1EXIq_76pPad6DefALKFKps2CDxNLRJi5&usp=sharing``` to your browser.
		- Add your place in the cscbank map. Add layer → Add marker will work.
## 3. Embed this map to your application to make it more valuable.
```
<iframe src="https://www.google.com/maps/d/embed?mid=1EXIq_76pPad6DefALKFKps2CDxNLRJi5&ll=51.9972972,4.3529887&z=17" height="100%" width="100%" frameborder="0" style="border:0;" allowfullscreen=""></iframe>
```