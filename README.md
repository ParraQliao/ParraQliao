/**
 * @name Cyan
 * @description Clean and Customizable, with custom background support
 * @author DaBluLite
 * @authorId 582170007505731594
 * @version 6.0.0
 * @updateUrl https://dablulite.github.io/Cyan/Cyan.theme.css
 * @source https://github.com/DaBluLite/Cyan
 * @invite 67VRpSjzxU
 */

/**
* Credits:
* Icons by Bootrstrap Icons
* Fonts by Google Fonts
*/
 
@import url("https://dablulite.github.io/Cyan/import.css");
:root {
	--cyan-interface-shadow: 0 4px 10px 0 rgb(0 0 0 / 60%);
	--cyan-font: 'Montserrat', 'Open Sans';
	--cyan-background-img: url(https://wallpaperswide.com/download/aero_stream_purple-wallpaper-1600x900.jpg);
	--cyan-accent-color: #b730b8;
	--cyan-blur: 48px;
	--cyan-radius-round-interface: 50px;
    --cyan-radius-interface: 24px;
    --cyan-radius-xl: 20px;
    --cyan-radius-large: 16px;
    --cyan-radius-medium: 12px;
    --cyan-radius-small: 8px;
    --cyan-radius-xs: 4px;
    --cyan-channelbar-width: 320px;
    --cyan-loading-header: "Polishing surfaces...";
}

.theme-dark,
.theme-dark .theme-light {
    --cyan-second-layer: rgb(0 0 0/20%);
    --cyan-background-primary: hsla(0deg 100% 0% / 20%);
    --cyan-bg-brightness: .7
}
.theme-light {
    --cyan-second-layer: rgb(255 255 255/60%);
    --cyan-background-primary: hsla(0deg 100% 100% / 60%)
}
