# Christopher Jones Photography

See it here: https://stopherjones.github.io/christopher-jones-photography/

An attempt to self-build and host a light-weight, modern, responsive photo gallery / portfolio, based on a few key aims and objectives:

1. **Performance**: 'Gallery' pages load small (max 600px) versions of each image in the gallery. No junk. No ads, no tracking, no analytics, no cookies. Mmm...cookies...drool... (no JS - in the backlog) 

2. **High resolution available**: Clicking on each gallery image loads a high resolution, full screen modal image. (one page done as proof of concept - https://stopherjones.github.io/christopher-jones-photography/Arts_and_theatre.html. Adding remaining modal images to website still in the backlog)

3. **Rows, not columns**: I prefer the row-based galleries that you see in Google Photos and Flickr, rather than the vertical card columns in Pinterest or the square grid favoured by Instagram. My aim was to achieve broadly equal height rows, where the images resize to fit the avilable space.

4. **Pages do not shunt around**: Intrinsic placeholders - still in the backlog

5. **HTML/CSS by default**: No real philosophical belief behind this, just feels like the more modern thing to do. Gallery pages and modal images use HTML / CSS only. (There is JS for the navbar, HTML / CSS only version in the backlog)

6. **Responsive**: Rows and photo cells respond to fill the browser window across mobile / tablet / desktop, and portrait / landscape. Based on CSS-Grid, with pages divided into width fractions. See https://medium.com/samsung-internet-dev/common-responsive-layouts-with-css-grid-and-some-without-245a862f48df for explanation and code.

7. **Free to host**: Or as close to free as possible. I don't want to make money from this (no ads) but ideally I'd not like it to cost me anything either. It's just a personal portfolio, I want to keep things as free and open as possible. 

8. **Android development**: Everything had to be possible to build and maintain from my Android tablet. 

More on points 7 and 8 below.


## Backlog

- Compatibility for older browsers
- Intrinsic placeholders
- Modal accessibility
- Remaining modal images
- HTML / CSS navbar
- Centralised navbar / footer (Jekyll?)


## Development and hosting

This site was built and hosted at no cost, and entirely from my Android tablet\*.

I wanted to build something I could maintain easily and cheaply. I've used a variety of portfolio platforms over the years - Wordpress, Blogger, Zenfolio, Flickr - but none of them give me everything I'm looking for - custom url, free to host, customisable layout etc

Github pages ticks pretty much all those boxes. I think the only thing I'm missing is server-side scripting. Whatever that is. 
 
I've also pretty much stopped using desktop PCs / laptops outside of work. They're either stuck on one desk, or the battery dies too quickly, or they get too clogged up and slow. I've been almost exclusively using an Android tablet for a couple of years now for everything from basic tasks, through to quite sophisticated tasks like importing and editing RAW photo files. The aim was to do the same building and hosting this site.

I have next to zero development skills or experience. I say next to no experience, because I have dabbled under the html / css bonnet before. I've even had cause to use the command line interface in anger (sometimes literally, as well as metaphorically) to run package managers and push web content to github. But all I've really done is ~~rip off someone else's work~~ follow instructions from others.
 
My workflow for this site is roughly as follows:
 
1. Google whatever it is I'm looking to do - set up a navbar, research photo gallery pages, build a modal etc
2. Copy their code into codepen.io
3. Play around in codepen until I get something I'm happy with
4. Get wildly out of my depth. Repeat steps 1-3 several times.
5. Finally export to local Android storage
6. Create an empty github repository at github.com and clone it to Android using the excellent Pocket Git (https://play.google.com/store/apps/details?id=com.aor.pocketgit)
7. Open, iterate and test files locally in anWriter free (https://play.google.com/store/apps/details?id=com.ansm.anwriter)
8. Push to github using Pocket Git

Android's split screen is a big help for multi-tasking. Having a seperate, bluetooth keyboard is a must.
This approach also means I can add minor changes on the go on my phone - like adding in this sentence ;) 
 
\* Ok, full disclosure...
* I pay for my custom url, but that's it.
* I already own the Android tablet, and Lightroom subscription so I'm not counting those towards the costs. Sunk costs and all that.
* I also re-sized the images in Adobe Lightroom for Windows. I tried a few Android re-sizing apps but found either the quality was lacking, or you had to pay to remove watermarks / quantity limits (see objective #7). Lightroom for Android just doesn't have the range of options that the desktop version has. I already owned the Windows device with Adobe Lightroom too, so I'm not counting that as a cost either.

## Credits and thanks

* Jo Franchetti, for the intro to CSS grids: https://medium.com/samsung-internet-dev/common-responsive-layouts-with-css-grid-and-some-without-245a862f48df
* W3 Schools, for the basic info and tutorials, especially styling and the nav bar https://www.w3schools.com
* Kevan Worrall, for the shutter-rose logo icon https://kevanworrall.myportfolio.com  