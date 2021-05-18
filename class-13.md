# LOCAL STORAGE

ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.

![local](https://res.cloudinary.com/de4rvmslk/image/upload/f_auto,q_auto,w_1440/LocalStorage-cover_photo.png)

## potentially dealbreaking downsides

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

## USING HTML5 STORAGE

![local](https://lh3.googleusercontent.com/proxy/MknhAUGGFOyEhj_bPL-Wg2gF1PkKlU7MkkC30djmbUZwdoPh-6i5tSHlbH1POUO6HAPzIoEk5G6UEdWb3btlY9YRsX7RC4Zb6i4mmWqfSvV528GI)

- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. 
- The named key is a string. 
- The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.
- the data is actually stored as a string.
 - If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

- other JavaScript objects, getItem setItem removeItem

![img](https://developer-chrome-com.imgix.net/image/BrQidfK9jaQyIHwdw91aVpkPiib2/8ou4ezYdLO8WdTlOljXY.png?auto=format)

## BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS
hile the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.

## BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS

While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visio