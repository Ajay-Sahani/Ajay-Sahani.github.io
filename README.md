# Ajay-Sahani.github.io
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.0.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' expr:lang='data:blog.localeUnderscoreDelimited' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
  
  
  <link href='https://ourancientearth.blogspot.com/?m=1' rel='canonical'/>
  <link href='https://ourancientearth.blogspot.com/' rel='canonical'/>
  
  <script async='async' custom-element='amp-auto-ads' src='https://cdn.ampproject.org/v0/amp-auto-ads-0.1.js'>
</script>
  
  <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
  <meta content='vfH1AViTM_9vzNb81baYxfqMq4n62HxbF2reOFw9ERc' name='google-site-verification'/>
  
  <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
  
<b:include name='theme-head'/>
<b:if cond='!data:view.isLayoutMode'>
<b:skin version='1.0.0'><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:         TechSpot
Version:      1.0.0 - Free
Author:       Pro Blogger Templates
Author Url:   https://probloggertemplates.com/
-----------------------------------------------*/

/*-- Customize Options (Start) --
<Variable name="keycolor" description="Main Color" type="color" default="#ff4422" value="#ff4422"/>
<Group description="Theme Options" selector="body">
    <Variable name="boxed" description="Boxed Mode" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="sidebar" description="Left Sidebar" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="fixedmenu" description="Fixed Menu" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="fixedsidebar" description="Fixed Sidebar" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Widths" selector="body">
    <Variable name="row.width" description="Container Width" type="length" default="1058px" min="970px" max="1094px" value="1058px"/>
    <Variable name="sidebar.width" description="Sidebar Width" type="length" default="300px" min="250px" max="336px" value="300px"/>
</Group>
<Group description="Fonts" selector="body">
    <Variable name="main.font" description="Main Font" type="font" family="Maven Pro" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="menu.font" description="Menu Font" type="font" family="Maven Pro" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="title.font" description="Title Font" type="font" family="Poppins" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="text.font" description="Text Font" type="font" family="Maven Pro" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
</Group>
<Group description="Background" selector="body">
	<Variable name="background.color" description="Body Background (Boxed)" type="color" default="#f4f6fa"  value="#f4f6fa"/>
    <Variable name="outer.bg" description="Outer Background" type="color" default="#ffffff"  value="#ffffff"/>
</Group>
<Group description="Colors" selector="body">
    <Variable name="main.color" description="Main Color" type="color" default="#ff4422" value="#ff4422"/>
    <Variable name="title.color" description="Title Color" type="color" default="#0a0a0a" value="#0a0a0a"/>
    <Variable name="title.hover.color" description="Title Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="meta.color" description="Meta Color" type="color" default="#a7aab2" value="#a7aab2"/>
    <Variable name="meta.link" description="Meta Link Color" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="text.color" description="Text Color" type="color" default="#505666"  value="#505666"/>
    <Variable name="border.color" description="Border Color" type="color" default="#efefef"  value="#efefef"/>
</Group>
<Group description="Header" selector="#header-wrapper">
    <Variable name="header.height" description="Height" type="length" default="60px" min="50px" max="70px" value="60px"/>
    <Variable name="header.bg1" description="Background (Left)" type="color" default="#ff4422" value="#ff4422"/>
    <Variable name="header.bg2" description="Background (Right)" type="color" default="#f4006f" value="#f4006f"/>
    <Variable name="header.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="header.hover.color" description="Hover Color" type="color" default="#fedde3" value="#fedde3"/>
    <Variable name="search.bg" description="Search Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="search.color" description="Search Color" type="color" default="$(text.color)" value="#505666"/>
    <Variable name="search.close" description="Search Close Icon" type="color" default="$(header.bg2)" value="#f4006f"/>
</Group>
<Group description="Sub Menu" selector="#header-wrapper">
    <Variable name="submenu.bg" description="Background" type="color" default="#0a0a0a" value="#0a0a0a"/>
    <Variable name="submenu.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="submenu.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
</Group>
<Group description="Header Bar" selector="nav.headerbar-wrap">
    <Variable name="headerbar.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="headerbar.title" description="Title Color" type="color" default="$(title.color)" value="#0a0a0a"/>
    <Variable name="headerbar.color" description="Link Color" type="color" default="$(text.color)" value="#505666"/>
    <Variable name="headerbar.hover.color" description="Link Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="social.bg" description="Social Background" type="color" default="$(submenu.bg)" value="#0a0a0a"/>
    <Variable name="social.color" description="Social Color" type="color" default="$(submenu.color)" value="#ffffff"/>
</Group>
<Group description="Mobile Menu" selector="body">
    <Variable name="mobilemenu.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="mobilemenu.color" description="Color" type="color" default="$(title.color)" value="#0a0a0a"/>
    <Variable name="mobilemenu.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
</Group>
<Group description="Widgets" selector="body">
    <Variable name="widget.title" description="Title Color" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="widget.title.size" description="Font Size" type="length" default="22px" min="18px" max="27px" value="22px"/>
</Group>
<Group description="Blog Posts" selector="body">
    <Variable name="gridstyle" description="Grid Style" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="summary" description="Show Summary" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="entrytag" description="Entry Tag" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Post Page" selector="body">
	<Variable name="topad.onpost" description="Show Top ADS" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="breadcrumb" description="Breadcrumbs" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="itempost.title.size" description="Title Font Size" type="length" default="37px" min="20px" max="50px" value="37px"/>
    <Variable name="itempost.content.size" description="Text Font Size" type="length" default="15px" min="12px" max="20px" value="15px"/>
    <Variable name="postnav" description="Navigation" type="length" default="1px" min="0px" max="1px" value="1px"/>
	<Variable name="footerad.onpost" description="Show Footer ADS" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Footer" selector="#footer-wrapper">
    <Variable name="footer.bg" description="Background" type="color" default="#0a0a0a" value="#0a0a0a"/>
    <Variable name="footer.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="footer.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="footer.text.color" description="Text Color" type="color" default="#a7aab2" value="#a7aab2"/>
    <Variable name="footer.border" description="Border Color" type="color" default="#1b1b1b" value="#1b1b1b"/>
</Group>
<Group description="Footer Bar" selector="div.footer-bar">
    <Variable name="footerbar.bg" description="Background" type="color" default="#000000" value="#000000"/>
    <Variable name="footerbar.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="footerbar.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#ff4422"/>
</Group>
<Group description="Buttons" selector="body">
    <Variable name="btn.bg" description="Background" type="color" default="$(main.color)" value="#ff4422"/>
    <Variable name="btn.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
</Group>
<Group description="Fix Blur (Fonts)" selector="body">
    <!-- Site Font -->
    <Variable name="mainfont.italic" description="Main Font Italic" type="font" default="italic 400 14px $(main.font.family)" value="italic 400 14px $(family)"/>
    <Variable name="mainfont.medium" description="Main Font Medium" type="font" default="normal 500 14px $(main.font.family)" value="normal 500 14px $(family)"/>
    <Variable name="mainfont.medium.italic" description="Main Font Medium Italic" type="font" default="italic 500 14px $(main.font.family)" value="italic 500 14px $(family)"/>
    <Variable name="mainfont.semibold" description="Main Font Semi Bold" type="font" default="normal 600 14px $(main.font.family)" value="normal 600 14px $(family)"/>
    <Variable name="mainfont.semibold.italic" description="Main Font Semi Bold Italic" type="font" default="italic 600 14px $(main.font.family)" value="italic 600 14px $(family)"/>
    <Variable name="mainfont.bold" description="Main Font Bold" type="font" default="normal 700 14px $(main.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="mainfont.bold.italic" description="Main Font Bold Italic" type="font" default="italic 700 14px $(main.font.family)" value="italic 700 14px $(family)"/>
    <!-- Menu Font -->
    <Variable name="menufont.bold" description="Menu Font Bold" type="font" default="normal 700 14px $(menu.font.family)" value="normal 700 14px $(family)"/>
    <!-- Title Font -->
    <Variable name="titlefont.bold" description="Title Font Bold" type="font" default="normal 700 14px $(title.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="titlefont.bold.italic" description="Title Font Bold Italic" type="font" default="italic 700 14px $(title.font.family)" value="italic 700 14px $(family)"/>
    <!-- Text Font -->
    <Variable name="textfont.italic" description="Text Font Italic" type="font" default="italic 400 14px $(text.font.family)" value="italic 400 14px $(family)"/>
    <Variable name="textfont.bold" description="Text Font Bold" type="font" default="normal 700 14px $(text.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="textfont.bold.italic" description="Text Font Bold Italic" type="font" default="italic 700 14px $(text.font.family)" value="italic 700 14px $(family)"/>
</Group>
<Variable name="body.background" description="Background" type="background" color="$(background.color)" default="$(color) none repeat fixed top left" value="$(color) none repeat fixed top left"/>
<Variable name="body.background.color" description="Comments Background" hideEditor="true" type="color" default="transparent"  value="transparent"/>
<Variable name="body.title.color" description="Comments Color" hideEditor="true" type="color" default="$(title.color)" value="#0a0a0a"/>
<Variable name="body.text.color" description="Comments Text Color" hideEditor="true" type="color" default="$(text.color)"  value="#505666"/>
<Variable name="body.link.color" description="Comments Link Color" hideEditor="true" type="color" default="$(main.color)"  value="#ff4422"/>
<Variable name="body.text.font" description="Comments Font 1" hideEditor="true" type="font" default="normal 400 14px poppins, Arial, sans-serif !important"  value="normal 400 14px poppins, Arial, sans-serif !important"/>
<Variable name="body.action.font.large" description="Comments Font 2" hideEditor="true" type="font" default="normal 700 14px poppins, Arial, sans-serif !important"  value="normal 700 14px poppins, Arial, sans-serif !important"/>
-- Customize Options (End) --*/

/*-- Google Fonts --*/
@font-face{font-family:'Maven Pro';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GwmQIAFg.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3Gw2QIAFg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GzWQI.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GwmQIAFg.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3Gw2QIAFg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GzWQI.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GwmQIAFg.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3Gw2QIAFg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GzWQI.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GwmQIAFg.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3Gw2QIAFg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF} @font-face{font-family:'Maven Pro';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/mavenpro/v25/7Au9p_AqnyWWAxW2Wk3GzWQI.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}

@font-face{font-family:'Poppins';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiGyp8kv8JHgFVrJJLucXtAKPY.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiGyp8kv8JHgFVrJJLufntAKPY.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiGyp8kv8JHgFVrJJLucHtA.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmg1hVFteOcEg.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmg1hVGdeOcEg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmg1hVF9eO.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmr19VFteOcEg.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmr19VGdeOcEg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmr19VF9eO.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmy15VFteOcEg.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmy15VGdeOcEg.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiDyp8kv8JHgFVrJJLmy15VF9eO.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiEyp8kv8JHgFVrJJbecmNE.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiEyp8kv8JHgFVrJJnecmNE.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiEyp8kv8JHgFVrJJfecg.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLGT9Z11lFc-K.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLGT9Z1JlFc-K.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLGT9Z1xlFQ.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLEj6Z11lFc-K.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLEj6Z1JlFc-K.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLEj6Z1xlFQ.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Poppins';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLCz7Z11lFc-K.woff2) format("woff2");unicode-range:U+0900-097F,U+1CD0-1CF6,U+1CF8-1CF9,U+200C-200D,U+20A8,U+20B9,U+25CC,U+A830-A839,U+A8E0-A8FB}
@font-face{font-family:'Poppins';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLCz7Z1JlFc-K.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Poppins';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/poppins/v15/pxiByp8kv8JHgFVrLCz7Z1xlFQ.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}

/*-- Material Icons Font --*/
@font-face{font-family:"Material Icons Round";font-display:swap;font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/materialiconsround/v65/LDItaoyNOAY6Uewc665JcIzCKsKc_M9flwmP.woff2) format("woff2")}.mir{font-family:"Material Icons Round";font-weight:400;font-style:normal;font-size:24px;line-height:1;letter-spacing:normal;text-transform:none;display:inline-block;white-space:nowrap;word-wrap:normal;direction:ltr;-webkit-font-feature-settings:liga;-webkit-font-smoothing:antialiased}icon:before{content:attr(name);font-family:'Material Icons Round';font-weight:400;font-style:normal;letter-spacing:normal;text-transform:none;white-space:nowrap;word-wrap:normal;direction:ltr;-webkit-font-feature-settings:liga;-webkit-font-smoothing:antialiased}@font-face{font-family:"PBT Icons";font-display:block;font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/materialiconsround/v65/LDItaoyNOAY6Uewc665JcIzCKsKc_M9flwmP.woff2) format("woff2")}

/*-- Font Awesome 5 Brands 5.15.4 --*/
@font-face{font-family:"Font Awesome 5 Brands";font-display:swap;font-style:normal;font-weight:400;src:url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.eot);src:url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.eot?#iefix) format("embedded-opentype"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.woff2) format("woff2"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.woff) format("woff"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.ttf) format("truetype"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.svg#fontawesome) format("svg")}.fab{font-family:"Font Awesome 5 Brands";font-weight:400}

/*-- CSS Variables --*/
:root{
--body-font:'$(main.font.family)', Arial, sans-serif;
--menu-font:'$(menu.font.family)', Arial, sans-serif;
--title-font:'$(title.font.family)', Arial, sans-serif;
--text-font:'$(text.font.family)', Arial, sans-serif;
--body-bg-color:$(background.color);
--body-bg:$(body.background);
--outer-bg:$(outer.bg);
--main-color:$(main.color);
--main-color-lite:$(main.color)50;
--title-color:$(title.color);
--title-hover-color:$(title.hover.color);
--meta-color:$(meta.color);
--meta-link-color:$(meta.link);
--text-color:$(text.color);
--header-bg-1:$(header.bg1);
--header-bg:linear-gradient(to right, $(header.bg1), $(header.bg2));
--header-color:$(header.color);
--header-hover-color:$(header.hover.color);
--search-bg:$(search.bg);
--search-color:$(search.color);
--search-close:$(search.close);
--submenu-bg:$(submenu.bg);
--submenu-color:$(submenu.color);
--submenu-hover-color:$(submenu.hover.color);
--headerbar-bg:$(headerbar.bg);
--headerbar-bg-lite:$(headerbar.bg)00;
--headerbar-title:$(headerbar.title);
--headerbar-color:$(headerbar.color);
--headerbar-hover-color:$(headerbar.hover.color);
--social-bg:$(social.bg);
--social-color:$(social.color);
--mobilemenu-bg:$(mobilemenu.bg);
--mobilemenu-color:$(mobilemenu.color);
--mobilemenu-hover-color:$(mobilemenu.hover.color);
--widget-title:$(widget.title);
--footer-bg:$(footer.bg);
--footer-color:$(footer.color);
--footer-hover-color:$(footer.hover.color);
--footer-text-color:$(footer.text.color);
--footer-border:$(footer.border);
--footerbar-bg:$(footerbar.bg);
--footerbar-color:$(footerbar.color);
--footerbar-hover-color:$(footerbar.hover.color);
--modal-bg:$(outer.bg);
--button-bg:$(btn.bg);
--button-color:$(btn.color);
--light-weight:400;
--title-weight:700;
--gray-bg:rgba(155,155,155,0.08);
--border-color:$(border.color);
--radius:3px;
}
html.rtl{
--body-font:'Cairo',Arial,sans-serif;
--menu-font:'Cairo',Arial,sans-serif;
--title-font:'Cairo',Arial,sans-serif;
--text-font:'Cairo',Arial,sans-serif;
}

/*-- Reset CSS --*/
html,body,a,abbr,acronym,address,applet,b,big,blockquote,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,input,button,h1,h2,h3,h4,h5,h6,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{padding:0;margin:0;border:0;outline:none;vertical-align:baseline;background:0 0;text-decoration:none}dl,ul{list-style-position:inside;list-style:none}ul li{list-style:none}caption{text-align:center}img{border:none;position:relative}a,a:visited{text-decoration:none}.clearfix{clear:both}.section,.widget,.widget ul{margin:0;padding:0}a{color:var(--main-color)}a img{border:0}abbr{text-decoration:none}.separator a{text-decoration:none!important;clear:none!important;float:none!important;margin-left:0!important;margin-right:0!important}#Navbar1,#navbar-iframe,.widget-item-control,a.quickedit,.home-link,.feed-links{display:none!important}.center{display:table;margin:0 auto;position:relative}.widget > h2,.widget > h3{display:none}.widget iframe,.widget img{max-width:100%}button,input,select,textarea{background:transparent;font-family:var(--body-font);-webkit-appearance:none;-moz-appearance:none;appearance:none;outline:none;border-radius:0}button{cursor:pointer}input[type="search"]::-webkit-search-cancel-button{-webkit-appearance:none}

/*-- Main CSS --*/
*{box-sizing:border-box}
html{position:relative;word-break:break-word;word-wrap:break-word;text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased;-webkit-text-size-adjust:100%}
body{position:relative;background:var(--body-bg);background-color:var(--body-bg-color);font-family:var(--body-font);font-size:14px;color:var(--text-color);font-weight:400;font-style:normal;line-height:1.4em}
.rtl{direction:rtl}
h1,h2,h3,h4,h5,h6{font-family:var(--title-font);font-weight:700}
a,input,textarea,button{transition:all .0s ease}
#outer-wrapper{position:relative;overflow:hidden;width:100%;max-width:100%;background-color:var(--outer-bg);margin:0 auto;padding:0}
.is-boxed #outer-wrapper{width:$(row.width + 60px);max-width:100%;box-shadow:0 0 20px rgba(0,0,0,0.05)}
.container{position:relative}
.row-x1{width:$(row.width);max-width:100%}
.row-x2{width:calc(100% - 40px)}
.row-x3{width:100%}
.flex-c{display:flex;justify-content:center}
.flex-col{display:flex;flex-direction:column}
.flex-sb{display:flex;justify-content:space-between}
#content-wrapper{float:left;width:100%;overflow:hidden;padding:30px 0}
.is-left #content-wrapper > .container,.rtl .is-right #content-wrapper > .container{flex-direction:row-reverse}
.rtl .is-left #content-wrapper > .container{flex-direction:row}
.theiaStickySidebar:before,.theiaStickySidebar:after{content:'';display:table;clear:both}
#main-wrapper{position:relative;width:calc(100% - $(sidebar.width + 30px))}
.no-sidebar #main-wrapper{width:100%}
#sidebar-wrapper{position:relative;width:$(sidebar.width)}
.no-sidebar #sidebar-wrapper{display:none}
.entry-thumbnail,.entry-avatar,.comments .avatar-image-container{display:block;position:relative;overflow:hidden;background-color:var(--gray-bg);z-index:5;color:transparent}
.thumbnail,.avatar{display:block;position:relative;width:100%;height:100%;background-size:cover;background-position:center center;background-repeat:no-repeat;z-index:1;transform-origin:center;opacity:0;transition:opacity .35s ease}
.thumbnail.pbt-lazy,.avatar.pbt-lazy{opacity:1}
.entry-thumbnail:hover .thumbnail,.cs:hover .entry-thumbnail .thumbnail{filter:brightness(1.03)}
.is-ytimg:after{position:absolute;content:'\e038';top:50%;right:50%;font-family:'Material Icons Round';font-size:46px;color:#fff;font-weight:400;z-index:5;transform:translate(50%,-50%);text-shadow:0 0 40px rgba(0,0,0,0.67);opacity:.65}
.sz-3.is-ytimg:after{transform:translate(50%,-50%) scale(.85)}
.sz-4.is-ytimg:after{transform:translate(50%,-50%) scale(.7)}
.is-ytimg:hover:after,.cs:hover .is-ytimg:after{opacity:1}
.cs .is-ytimg:after{top:15px;right:15px;line-height:1;transform:translate(0)}
.rtl .cs .is-ytimg:after{left:15px;right:unset}
.popular-items .cs .is-ytimg:after,.FeaturedPost .is-ytimg:after{top:10px;right:10px;font-size:40px}
.rtl .popular-items .cs .is-ytimg:after,.rtl .FeaturedPost .is-ytimg:after{left:10px;right:unset}
.entry-category{display:flex;align-items:center;width:-moz-fit-content;width:fit-content;height:20px;background-color:#ffffff25;font-size:12px;color:#fff;font-weight:500;text-transform:uppercase;z-index:2;padding:0 8px;margin:0 0 10px;border-radius:var(--radius)}
.entry-header{display:flex;flex-direction:column}
.entry-title{color:var(--title-color);font-weight:var(--title-weight);line-height:1.3em}
.entry-title a{display:block;color:var(--title-color)}
.entry-title a:hover{color:var(--title-hover-color)}
.entry-meta{display:flex;font-size:12px;color:var(--meta-color);font-weight:var(--light-weight);margin:4px 0 0}
.entry-meta .mi{display:flex}
.entry-meta .mi,.entry-meta .sp{margin:0 4px 0 0}
.rtl .entry-meta .mi,.rtl .entry-meta .sp{margin:0 0 0 4px}
.entry-meta .author-name{color:var(--meta-link-color);font-weight:500}
.excerpt{font-family:var(--text-font);color:var(--text-color);font-weight:var(--light-weight);line-height:1.5em}
.cs .entry-inner{display:block;position:relative;width:100%;height:100%;overflow:hidden}
.mask:before{content:'';position:absolute;top:0;left:0;right:0;bottom:0;background:linear-gradient(to top,rgba(0,0,0,0.25),rgba(0,0,0,0.0));-webkit-backface-visibility:hidden;backface-visibility:hidden;z-index:2;opacity:1;margin:0;transition:opacity .25s ease}
.entry-info{position:absolute;left:0;bottom:0;width:100%;background:linear-gradient(to top,rgba(0,0,0,0.9),rgba(0,0,0,0));overflow:hidden;text-shadow:0 1px 2px rgba(0,0,0,0.1);z-index:10;padding:15px}
.entry-info .entry-title{display:-webkit-box;-webkit-line-clamp:3;-webkit-box-orient:vertical;color:#fff;overflow:hidden}
.entry-info .entry-meta{color:#cccdcd}
.entry-info .entry-meta .author-name{color:#e5e5e5}
.entry-info .entry-category{text-shadow:none}
.btn{position:relative;border-radius:var(--radius)}
@keyframes pbtSpinner{0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}
.loader{position:relative;width:100%;height:100%;overflow:hidden;display:flex;align-items:center;justify-content:center;margin:0}
.loader:after{content:'';display:block;width:30px;height:30px;box-sizing:border-box;margin:0;border:2px solid var(--main-color-lite);border-left-color:var(--main-color);border-radius:100%;animation:pbtSpinner .5s infinite linear;transform-origin:center}
.error-msg{display:flex;align-items:center;font-size:14px;color:var(--meta-color);padding:20px 0;font-weight:400}
.social-error{display:flex;align-items:center}
.social-error:before{content:'\e001';font-family:'Material Icons Round';font-size:14px;font-weight:400;margin:0 3px 0 0}
.rtl .social-error:before{margin:0 0 0 3px}
.overlay{visibility:hidden;opacity:0;position:fixed;top:0;left:0;right:0;bottom:0;background-color:rgba(22,22,26,0.6);-webkit-backdrop-filter:blur(2px);-ms-backdrop-filter:blur(2px);-o-backdrop-filter:blur(2px);backdrop-filter:blur(2px);z-index:1000;margin:0;transition:all .25s ease}
.social a:before{display:block;font-family:'Font Awesome 5 Brands';font-style:normal;font-weight:400}
.social .rss a:before,.social .share a:before,.social .email a:before,.social .external-link a:before{content:'\e0e5';font-family:'Material Icons Round'}
.social .share a:before{content:'\e80d'}
.social .email a:before{content:'\e0be'}
.social .external-link a:before{content:'\e89e'}
.color .blogger a{color:#1a73e8}
.color .blogger a{color:#ff5722}
.color .apple a{color:#333}
.color .amazon a{color:#fe9800}
.color .microsoft a{color:#0067B8}
.color .facebook a,.color .facebook-f a{color:#3b5999}
.color .twitter a{color:#00acee}
.color .youtube a{color:#e60023}
.color .instagram a{color:#dd277b;--instagram:linear-gradient(15deg,#ffb13d,#dd277b,#4d5ed4)}
.color .pinterest a,.color .pinterest-p a{color:#e60023}
.color .dribbble a{color:#ea4c89}
.color .linkedin a{color:#0077b5}
.color .tumblr a{color:#365069}
.color .twitch a{color:#9147ff}
.color .rss a{color:#ffc200}
.color .skype a{color:#00aff0}
.color .stumbleupon a{color:#eb4823}
.color .vk a{color:#4a76a8}
.color .stack-overflow a{color:#f48024}
.color .github a{color:#24292e}
.color .soundcloud a{color:#ff7400}
.color .behance a{color:#191919}
.color .digg a{color:#1b1a19}
.color .delicious a{color:#0076e8}
.color .codepen a{color:#000}
.color .flipboard a{color:#f52828}
.color .reddit a{color:#ff4500}
.color .whatsapp a{color:#3fbb50}
.color .messenger a{color:#0084ff}
.color .snapchat a{color:#ffe700}
.color .telegram a{color:#179cde}
.color .steam a{color:#112c5b}
.color .discord a{color:#7289da}
.color .quora a{color:#b92b27}
.color .tiktok a{color:#fe2c55}
.color .share a{color:var(--meta-color)}
.color .email a{color:#888}
.color .external-link a{color:var(--title-color)}
#header-wrapper{position:relative;float:left;width:100%;z-index:50;box-shadow:0 0 25px rgba(0,0,0,0.10)}
.rtl:not(.is-dark) #header-wrapper{--header-bg:linear-gradient(to left, $(header.bg1), $(header.bg2))}
.main-header,.header-inner,.header-header{float:left;width:100%;height:$(header.height);background-color:var(--header-bg-1);background:var(--header-bg)}
.header-inner{background-color:rgba(0,0,0,0);background:rgba(0,0,0,0)}
.header-inner.is-fixed .header-header{box-shadow:0 0 25px rgba(0,0,0,0.10)}
.header-inner.is-fixed{position:fixed;top:-$(header.height * 2);left:0;width:100%;z-index:990;backface-visibility:hidden;visibility:hidden;opacity:0;transform:translate3d(0,0,0);transition:all .25s ease-in-out}
.header-inner.is-fixed.show{visibility:visible;opacity:1;transform:translate3d(0,$(header.height * 2),0)}
.is-boxed .header-header{float:none;width:$(row.width + 60px);max-width:100%;margin:0 auto;padding:0}
.header-items{position:relative;display:flex;flex-wrap:wrap;justify-content:space-between}
.flex-left{display:flex;align-items:center;z-index:15;transition:all .17s ease}
.flex-right{display:flex;align-items:center;position:absolute;top:0;right:0;height:$(header.height);z-index:15;transition:all .17s ease}
.rtl .flex-right{left:0;right:unset}
.main-logo{display:flex;align-items:center;flex-shrink:0;height:$(header.height);overflow:hidden;margin:0 28px 0 0}
.rtl .main-logo{margin:0 0 0 28px}
.main-logo img{display:block;width:auto;height:auto;max-height:40px}
.main-logo .title{max-width:100%;font-size:25px;color:var(--header-color);line-height:40px;font-weight:700;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}
.main-logo .title a{color:var(--header-color)}
.main-logo .title a:hover{color:var(--header-hover-color)}
.main-logo #h1-off{display:none;visibility:hidden}
#xdfcb-main-menu{z-index:10}
#xdfcb-main-menu .widget,#xdfcb-main-menu .widget > .widget-title{display:none}
#xdfcb-main-menu .widget.is-ready{display:block}
.main-nav{display:flex;height:$(header.height)}
.main-nav > li{position:relative;display:flex;flex-shrink:0}
.main-nav > li + li{margin:0 0 0 28px}
.rtl .main-nav > li + li{margin:0 28px 0 0}
.main-nav > li > a{display:flex;align-items:center;font-family:var(--menu-font);font-size:14px;color:var(--header-color);font-weight:700;text-transform:uppercase}
.main-nav > li > a > icon{display:inline-block;font-size:16px;line-height:1;margin:0 3px 0 0}
.rtl .main-nav > li > a > icon{margin:0 0 0 3px}
.main-nav > li:hover > a{color:var(--header-hover-color)}
.main-nav .has-sub > a:after{display:inline-block;content:'\e5cf';font-family:'Material Icons Round';font-size:16px;font-weight:400;margin:-4px 0 0 2px}
.rtl .main-nav .has-sub > a:after{margin:-4px 2px 0 0}
.main-nav .sub-menu,.main-nav .ul{position:absolute;left:0;top:$(header.height);width:180px;background-color:var(--submenu-bg);z-index:99999;padding:6px 0;backface-visibility:hidden;visibility:hidden;opacity:0;box-shadow:0 1px 2px rgba(0,0,0,0.05),0 5px 10px 0 rgba(0,0,0,0.05)}
.rtl .main-nav .sub-menu,.rtl .main-nav .ul{left:auto;right:0}
.main-nav .sub-menu.sm-1{left:-14px}
.rtl .main-nav .sub-menu.sm-1{left:unset;right:-14px}
.main-nav .sub-menu.sm-2{top:-6px;left:100%}
.rtl .main-nav .sub-menu.sm-2{left:unset;right:100%}
.main-nav .sub-menu li{position:relative;display:block}
.main-nav .sub-menu li a{display:flex;justify-content:space-between;font-size:14px;color:var(--submenu-color);padding:8px 15px}
.main-nav .sub-menu li:hover > a{color:var(--submenu-hover-color)}
.main-nav .sub-menu > .has-sub > a:after{content:'\e5cc';margin:0 -5px}
.rtl .main-nav .sub-menu > .has-sub > a:after{content:'\e5cb'}
.main-nav .sub-menu,.main-nav .ul{transition:all .17s ease}
.main-nav li:hover > .sub-menu,.main-nav li:hover .ul{backface-visibility:inherit;visibility:visible;opacity:1}
.mobile-menu-toggle{display:none;height:34px;font-size:26px;color:var(--header-color);align-items:center;padding:0 13px 0 16px}
.rtl .mobile-menu-toggle{padding:0 16px 0 13px}
.mobile-menu-toggle:after{content:'\e5d2';font-family:'Material Icons Round';font-weight:400}
.mobile-menu-toggle:hover{color:var(--header-hover-color)}
.toggle-wrap{display:flex;align-items:center;z-index:20}
@keyframes pbtOn{0%{opacity:0}100%{opacity:1}}
@keyframes pbtOff{0%{opacity:0}100%{opacity:1}}
.search-toggle{display:flex;align-items:center;justify-content:center;width:38px;height:38px;background-color:var(--gray-bg);color:var(--header-color);font-size:24px}
.search-toggle:before{display:block;content:'\e8b6';font-family:'Material Icons Round';font-weight:400}
.search-toggle:hover{color:var(--header-hover-color)}
@keyframes pbtSearch{0%{width:80%;opacity:0}100%{width:100%;opacity:1}}
.main-search{display:none;align-items:center;justify-content:flex-end;position:absolute;top:0;right:0;width:$(sidebar.width);height:$(header.height);z-index:25;transition:all 0s ease}
.rtl .main-search{left:0;right:unset}
.main-search .search-form{display:flex;align-items:center;float:right;width:100%;height:38px;background-color:var(--search-bg);border-radius:var(--radius);box-shadow:0 0 8px rgba(0,0,0,0.1);animation:pbtSearch .17s ease}
.rtl .main-search .search-form{float:left}
.main-search .search-input{width:100%;flex:1;font-family:inherit;font-size:16px;color:var(--search-color);font-weight:var(--light-weight);text-align:left;padding:0 12px}
.rtl .main-search .search-input{text-align:right}
.main-search .search-input::placeholder{color:var(--search-color);opacity:.65;outline:none}
.main-search .search-toggle{background-color:transparent;color:var(--search-close)}
.main-search .search-toggle:before{content:'\e5cd'}
.main-search .search-toggle:hover{opacity:.9}
.search-active .flex-right{visibility:hidden;opacity:0}
.headerbar-wrap{position:relative;float:left;width:100%;height:36px;background-color:var(--headerbar-bg);z-index:2}
.headerbar-items{position:relative;width:100%}
.headerbar{width:100%;flex:1}
.hb-menu{position:relative;width:100%;overflow:hidden}
.hb-menu:before,.hb-menu:after{content:'';position:absolute;top:0;left:-20px;width:20px;height:36px;background:linear-gradient(to left,var(--headerbar-bg-lite),var(--headerbar-bg));z-index:2;opacity:0}
.hb-menu:after{left:unset;right:0;background:linear-gradient(to right,var(--headerbar-bg-lite),var(--headerbar-bg))}
.rtl .hb-menu:before{left:0}
.rtl .hb-menu:after{right:-20px}
.hb-menu ul{display:flex;width:100%;overflow:hidden;overflow-x:auto;-webkit-overflow-scrolling:touch;z-index:1}
.hb-menu ul li{flex-shrink:0;font-size:12px;line-height:36px;font-weight:500;text-transform:uppercase}
.hb-menu ul li + li{margin:0 0 0 24px}
.rtl .hb-menu ul li + li{margin:0 24px 0 0}
.hb-menu ul .title{display:flex;align-items:center;font-size:13px;color:var(--headerbar-title);font-weight:700}
.hb-menu ul .title:before{content:'\ea0b';font-family:'Material Icons Round';font-size:16px;font-weight:400;margin:0 -3px}
.hb-menu ul .title span{margin:0 0 0 3px}
.rtl .hb-menu ul .title span{margin:0 3px 0 0}
.hb-menu li a{display:block;color:var(--headerbar-color)}
.hb-menu li a:hover{color:var(--headerbar-hover-color)}
.social-toggle{display:flex;align-items:center;flex-shrink:0;height:36px;background-color:var(--headerbar-bg);font-size:12px;color:var(--headerbar-color);font-weight:500;text-transform:uppercase;overflow:hidden;z-index:10;padding:0 0 0 10px}
.rtl .social-toggle{left:0;right:unset;padding:0 10px 0 0}
.social-toggle:after{display:inline-block;content:'\e80d';font-family:'Material Icons Round';font-size:15px;font-weight:400;margin:0 0 0 4px}
.rtl .social-toggle:after{margin:0 4px 0 0}
.social-active .social-toggle:after{content:'\e5cd';font-size:18px;margin:0 -2px 0 3px}
.rtl .social-active .social-toggle:after{margin:0 3px 0 -2px}
.social-toggle:hover{color:var(--headerbar-hover-color)}
.social-toggle.social-on:after{animation:pbtOn .5s ease}
.social-toggle.social-off:after{animation:pbtOff .5s ease}
.hb-icons{position:absolute;top:100%;right:0;min-width:150px;background-color:var(--social-bg);overflow:hidden;z-index:15;box-shadow:0 1px 2px rgba(0,0,0,0.05),0 5px 10px 0 rgba(0,0,0,0.05);backface-visibility:hidden;visibility:hidden;opacity:0;transition:all .17s ease}
.rtl .hb-icons{left:0;right:unset}
.social-active .hb-icons{backface-visibility:inherit;visibility:visible;opacity:1}
.hb-icons ul{padding:20px}
.hb-icons ul li + li{margin:14px 0 0}
.hb-icons li a{display:flex;align-items:center;font-size:14px}
.hb-icons li a:before{font-size:15px}
.hb-icons li span{color:var(--social-color);padding:0 8px}
.hb-icons li a:hover span{color:currentColor}
.hb-icons .social-error{font-size:13px;color:var(--social-color);padding:20px}
#slide-menu{display:none;position:fixed;width:300px;height:100%;top:0;left:0;bottom:0;background-color:var(--mobilemenu-bg);overflow:hidden;z-index:1010;left:0;-webkit-transform:translate3d(-100%,0,0);transform:translate3d(-100%,0,0);visibility:hidden;box-shadow:3px 0 10px rgba(0,0,0,0.1);transition:all .25s ease}
.rtl #slide-menu{left:unset;right:0;-webkit-transform:translate3d(100%,0,0);transform:translate3d(100%,0,0)}
.nav-active #slide-menu,.rtl .nav-active #slide-menu{-webkit-transform:translate3d(0,0,0);transform:translate3d(0,0,0);visibility:visible}
.slide-menu-header{height:$(header.height);background:var(--header-bg);overflow:hidden;display:flex;align-items:center;justify-content:space-between;box-shadow:0 1px 8px rgba(0,0,0,0.1)}
.mobile-logo{display:flex;flex:1;width:100%;overflow:hidden;padding:0 0 0 20px}
.rtl .mobile-logo{padding:0 20px 0 0}
.mobile-logo .homepage{max-width:100%;font-size:25px;color:var(--header-color);line-height:40px;font-weight:700;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}
.mobile-logo .homepage:hover{color:var(--header-hover-color)}
.mobile-logo .logo-img img{display:block;width:auto;max-width:100%;height:auto;max-height:40px}
.hide-mobile-menu{display:flex;height:100%;color:var(--header-color);font-size:26px;align-items:center;z-index:20;padding:0 15px}
.hide-mobile-menu:before{content:'\e5cd';font-family:'Material Icons Round';font-weight:400}
.hide-mobile-menu:hover{color:var(--header-hover-color)}
.slide-menu-flex{display:flex;height:calc(100% - $(header.height));flex-direction:column;justify-content:space-between;overflow:hidden;overflow-y:auto;-webkit-overflow-scrolling:touch}
.mobile-menu{padding:20px}
.mobile-menu .sub-menu{display:none;grid-column:1/3;overflow:hidden}
.mobile-menu ul li a{display:block;font-size:14px;color:var(--mobilemenu-color);font-weight:400;padding:10px 0}
.mobile-menu > ul > li > a{font-family:var(--menu-font);font-weight:700;text-transform:uppercase}
.mobile-menu li.has-sub{display:grid;grid-template-columns:1fr 26px}
.mobile-menu .submenu-toggle{display:flex;align-items:center;justify-content:center;align-self:center;height:26px;background-color:var(--gray-bg);font-size:24px;color:var(--mobilemenu-color)}
.mobile-menu .submenu-toggle:before{content:'\e5cf';font-family:'Material Icons Round';font-weight:400}
.mobile-menu .expanded > .submenu-toggle:before{content:'\e5ce'}
.mobile-menu ul li a:hover,.mobile-menu .submenu-toggle:hover{color:var(--mobilemenu-hover-color)}
.mobile-menu li.has-sub li a{font-size:14px;opacity:.75;padding:10px 15px}
.mobile-menu li.has-sub li li a{padding:10px 30px}
.mm-footer{padding:20px}
.mm-footer ul{display:flex;flex-wrap:wrap}
.mm-footer li{margin:0 15px 0 0}
.rtl .mm-footer li{margin:0 0 0 15px}
.mm-footer li:last-child{margin:0}
.mm-footer .link-list{margin:10px 0 0}
.mm-footer .link-list li{margin-top:5px}
.mm-footer a{display:block;font-size:14px;color:var(--mobilemenu-color)}
.mm-footer .social a{font-size:15px}
.mm-footer .social .rss a,.mm-footer .social .email a,.mm-footer .social .external-link a{font-size:18px}
.mm-footer .social a:hover{opacity:.9}
.mm-footer .link-list a:hover{color:var(--mobilemenu-hover-color)}
.title-wrap{display:flex;align-items:center;justify-content:space-between;margin:0 0 20px}
.title-wrap > .title{display:flex;align-items:center;flex:1;position:relative;font-size:$(widget.title.size);color:var(--widget-title);line-height:1}
#main-wrapper .title-wrap > .title:after{display:inline-block;content:'\e5cc';font-family:'Material Icons Round';font-size:22px;font-weight:400;line-height:0;margin:3px 0 0 -4px}
.rtl #main-wrapper .title-wrap > .title:after{content:'\e5cb';margin: 3px -4px 0 0}
.title-wrap > .title-link{max-width:fit-content;font-size:14px;color:var(--meta-color);line-height:1;font-weight:var(--light-weight)}
.title-wrap > .title-link:hover{color:var(--main-color)}
.list-items{display:grid;grid-template-columns:1fr;grid-gap:30px}
.list-items .post{display:flex;border-top:1px solid var(--border-color)}
.list-items .entry-thumbnail{width:270px;max-width:50%;height:155px;margin:-1px 0 0}
.list-items .entry-header{flex:1;padding:16px 0 0 20px}
.rtl .list-items .entry-header{padding:16px 20px 0 0}
.list-items .entry-title{font-size:19px}
.list-items .entry-excerpt{font-size:14px;margin:6px 0 0}
.list-items .entry-meta{flex-wrap:wrap;font-size:13px;margin:6px 0 0}
.grid-items{display:grid;grid-template-columns:repeat(2,1fr);grid-gap:30px}
.grid-items .post{display:flex;flex-direction:column}
.grid-items .entry-thumbnail{width:100%;height:184px;margin:0 0 16px}
.grid-items .entry-title{font-size:20px}
.grid-items .entry-excerpt{display:-webkit-box;font-size:14px;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical;margin:6px 0 0}
.grid-items .entry-meta{flex-wrap:wrap;font-size:13px;margin:6px 0 0}
#main,.index-blog{float:left;width:100%}
.queryMessage .query-info{display:flex;align-items:center;font-family:var(--title-font);font-size:$(widget.title.size);color:var(--widget-title);font-weight:var(--title-weight);line-height:1;margin:0 0 20px}
.no-posts .queryMessage .query-info{margin:0}
.queryMessage .query-info:after{display:inline-block;content:'\e5cc';font-family:'Material Icons Round';font-size:22px;color:var(--main-color);font-weight:400;line-height:0;margin:3px 0 0 -4px}
.rtl .queryMessage .query-info:after{content:'\e5cb';margin:3px -4px 0 0}
.queryEmpty{font-size:14px;color:var(--meta-color);text-align:center;margin:50px 0}
.index-post-wrap .post.ad-type{display:block;border:0}
@keyframes pbtFadeInUp{0%{opacity:0;transform:translate3d(0,10px,0)}100%{opacity:1;transform:translate3d(0,0,0)}}
.index-post-wrap .post.fadeInUp{animation:pbtFadeInUp .5s ease}
#breadcrumb{display:flex;font-size:14px;color:var(--meta-color);font-weight:var(--light-weight);line-height:1;margin:0 0 12px}
#breadcrumb a{color:var(--meta-color)}
#breadcrumb a.home,#breadcrumb a:hover{color:var(--main-color)}
#breadcrumb .separator:after{content:'\e5cc';font-family:'Material Icons Round';font-size:16px;font-weight:400;font-style:normal;vertical-align:middle}
.rtl #breadcrumb .separator:after{content:'\e5cb'}
.item-post h1.entry-title{font-size:$(itempost.title.size);font-weight:700;line-height:1.2em}
.p-eh .entry-meta{justify-content:space-between;font-size:14px;margin:13px 0 0}
.entry-meta .align-left,.entry-meta .align-right{display:flex;align-items:center}
.p-eh .entry-meta .mi,.p-eh .entry-meta .sp{margin:0 4px 0 0}
.rtl .entry-meta .mi,.rtl .p-eh .entry-meta .sp{margin:0 0 0 4px}
.entry-meta .entry-avatar{width:34px;height:34px;overflow:hidden;padding:1px;margin:0 6px 0 0;border:1px solid var(--main-color);border-radius:50%}
.rtl .entry-meta .entry-avatar{margin:0 0 0 6px}
.entry-meta .avatar{z-index:2;border-radius:50%}
.entry-meta .al-items{display:flex}
.share-toggle{display:flex;align-items:center;justify-content:center;width:32px;height:32px;background-color:var(--gray-bg);color:var(--title-color);font-size:18px;border-radius:var(--radius)}
.share-toggle:before{display:block;content:'\e80d';font-family:'Material Icons Round';line-height:0;font-weight:400}
.rtl .share-toggle:before{transform:rotate3d(0,1,0,180deg)}
.share-toggle:hover{color:var(--title-hover-color)}
.entry-content-wrap{padding:25px 0 0}
#post-body{position:relative;float:left;width:100%;font-family:var(--text-font);font-size:$(itempost.content.size);color:var(--text-color);line-height:1.6em}
.post-body p{margin-bottom:25px}
.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{font-size:17px;color:var(--title-color);line-height:1.3em;margin:0 0 20px}
.post-body h1{font-size:26px}
.post-body h2{font-size:23px}
.post-body h3{font-size:20px}
.post-body img{height:auto!important}
blockquote{position:relative;background-color:var(--gray-bg);color:var(--title-color);font-style:normal;padding:20px;margin:0;border-radius:var(--radius)}
blockquote:before{position:absolute;top:0;left:5px;content:'\e244';font-family:'Material Icons Round';font-size:60px;color:var(--title-color);font-style:normal;font-weight:400;line-height:1;opacity:.05;margin:0}
.rtl blockquote:before{left:unset;right:5px}
.post-body ul{padding:0 0 0 20px;margin:10px 0}
.rtl .post-body ul{padding:0 20px 0 0}
.post-body li{margin:8px 0;padding:0}
.post-body ul li,.post-body ol ul li{list-style:none}
.post-body ul li:before,.post-body ul li ul li ul li:before{display:inline-block;content:'\ef4a';font-family:'Material Icons Round';font-size:.4em;line-height:1;vertical-align:middle;margin:0 5px 0 0}
.post-body ul li ul li:before{content:'\e57b'}
.rtl .post-body ul li:before{margin:0 0 0 5px}
.post-body ol{counter-reset:pbt;padding:0 0 0 20px;margin:10px 0}
.rtl .post-body ol{padding:0 20px 0 0}
.post-body ol > li{counter-increment:pbt;list-style:none}
.post-body ol > li:before{display:inline-block;content:counters(pbt,'.')'.';margin:0 5px 0 0}
.rtl .post-body ol > li:before{margin:0 0 0 5px}
.post-body u{text-decoration:underline}
.post-body strike{text-decoration:line-through}
.post-body sup{vertical-align:super}
.post-body a{color:var(--main-color)}
.post-body a:hover{text-decoration:underline}
.post-body a.button{display:inline-block;height:36px;background-color:var(--button-bg);font-family:var(--body-font);font-size:15px;color:var(--button-color);font-weight:400;line-height:36px;text-align:center;text-decoration:none;cursor:pointer;padding:0 20px;margin:0 6px 8px 0}
.rtl .post-body a.button{margin:0 0 8px 6px}
.post-body a.button.x2{height:46px;font-size:18px;line-height:46px}
.post-body a.button.is-c,.rtl.post-body a.button.is-c{margin:0 3px 8px}
.post-body a.button.x2 span{display:inline-block;background-color:rgba(255,255,255,0.1);font-size:14px;line-height:14px;padding:6px;margin:0 0 0 20px;border-radius:var(--radius)}
.rtl .post-body a.button.x2 span{margin:0 20px 0 0}
.post-body .button:before{display:inline-block;font-family:'Material Icons Round';font-size:16px;font-weight:400;line-height:1;vertical-align:middle;margin:-1px 6px 0 0}
.rtl .post-body .button:before{margin:-1px 0 0 6px}
.post-body a.btn.x2:before{font-size:20px;margin:-2px 6px 0 0}
.rtl .post-body a.btn.x2:before{margin:-2px 0 0 6px}
.post-body .btn.preview:before{content:'\e8f4'}
.post-body .btn.download:before{content:'\f090'}
.post-body .btn.link:before{content:'\e157'}
.post-body .btn.cart:before{content:'\e8cc'}
.post-body .btn.info:before{content:'\e88e'}
.post-body .btn.share:before{content:'\e80d'}
.post-body .btn.contact:before{content:'\e0e1'}
.post-body .btn.whatsapp:before{content:'\f232';font-family:'Font Awesome 5 Brands';font-style:normal}
.post-body .btn.paypal:before{content:'\f1ed';font-family:'Font Awesome 5 Brands';font-style:normal}
.post-body .btn.gift:before{content:'\e8f6'}
.post-body a.color{color:#fff}
.post-body a.button:hover{opacity:.9}
.alert-message{display:block;background-color:var(--gray-bg);padding:20px;border:1px solid var(--border-color);border-radius:var(--radius)}
.alert-message.alert-success{background-color:rgba(39,174,96,0.1);color:rgba(39,174,96,1);border-color:rgba(39,174,96,0.1)}
.alert-message.alert-info{background-color:rgba(41,128,185,0.1);color:rgba(41,128,185,1);border-color:rgba(41,128,185,0.1)}
.alert-message.alert-warning{background-color:rgba(243,156,18,0.1);color:rgba(243,156,18,1);border-color:rgba(243,156,18,0.1)}
.alert-message.alert-error{background-color:rgba(231,76,60,0.1);color:rgba(231,76,60,1);border-color:rgba(231,76,60,0.1)}
.alert-message:before{display:inline-block;font-family:'Material Icons Round';font-size:18px;line-height:1;font-weight:400;vertical-align:middle;margin:0 5px 0 0}
.rtl .alert-message:before{margin:0 0 0 5px}
.alert-message.alert-success:before{content:'\e86c'}
.alert-message.alert-info:before{content:'\e88e'}
.alert-message.alert-warning:before{content:'\e000'}
.alert-message.alert-error:before{content:'\e5c9'}
.post-body table{width:100%;overflow-x:auto;text-align:left;margin:0;border-collapse:collapse;border:1px solid var(--border-color)}
.rtl .post-body table{text-align:right}
.post-body table td,.post-body table th{padding:6px 12px;border:1px solid var(--border-color)}
.post-body table thead th{color:var(--title-color);vertical-align:bottom}
table.tr-caption-container,table.tr-caption-container td,table.tr-caption-container th{line-height:1;padding:0;border:0}
table.tr-caption-container td.tr-caption{font-size:12px;color:var(--meta-color);font-style:italic;padding:6px 0 0}
.post-body .contact-form-widget{display:table;width:100%;font-family:var(--body-font)}
.post-body .contact-form-widget .cf-s{font-size:15px}
.post-body .contact-form-name.cf-s{width:calc(50% - 5px)}
.rtl .post-body .contact-form-name{float:right}
.post-body .contact-form-email.cf-s{float:right;width:calc(50% - 5px)}
.rtl .post-body .contact-form-email{float:left}
.post-body .contact-form-button-submit{font-size:15px}
.post-body pre,pre.code-box{display:block;background-color:var(--gray-bg);font-family:Monospace;font-size:13px;color:var(--title-color);white-space:pre-wrap;line-height:1.4em;padding:20px;border:1px solid var(--border-color);border-radius:var(--radius)}
.post-body .google-auto-placed{margin:25px 0}
.youtube-video{position:relative;width:100%;padding:0;padding-top:56%}
.youtube-video iframe{position:absolute;top:0;left:0;width:100%;height:100%}
.entry-labels{display:flex;flex-wrap:wrap;margin:20px 0 0}
.entry-labels > *{display:flex;align-items:center;height:20px;background-color:var(--gray-bg);font-size:12px;color:var(--title-color);padding:0 6px;margin:5px 5px 0 0}
.rtl .entry-labels > *{margin:5px 0 0 5px}
.entry-labels span{background-color:var(--title-color);color:var(--outer-bg)}
.entry-labels a:hover{color:var(--title-hover-color)}
.post-share{margin:20px 0 0}
ul.share-a{display:flex;flex-wrap:wrap;align-items:flex-start}
.share-a .btn{display:flex;align-items:center;justify-content:center;width:36px;height:36px;background-color:currentColor;font-size:16px;font-weight:400;overflow:hidden;margin:5px 5px 0 0}
.rtl .share-a .btn{margin:5px 0 0 5px}
.share-a .email .btn{font-size:18px}
.share-a .has-span .btn{width:auto;justify-content:space-between;padding:4px}
.share-a .has-span .btn:before{display:flex;align-items:center;justify-content:center;flex-shrink:0;width:32px;height:28px;background-color:rgba(255,255,255,0.08);border-radius:var(--radius)}
.share-a .btn:before{color:#fff}
.share-a .btn span{font-size:14px;color:#fff;padding:0 15px}
.share-a .sl-btn{position:relative;background-color:var(--outer-bg);font-size:18px;color:var(--title-color);overflow:visible;margin:5px 10px 0 0;border:1px solid var(--border-color);border-radius:var(--radius)}
.share-a .sl-btn:before,.share-a .sl-btn:after{position:absolute;content:'';height:0;width:0;pointer-events:none;top:calc(50% - 6px);right:-12px;border:6px solid transparent;border-left-color:var(--border-color)}
.share-a .sl-btn:after{top:calc(50% - 5px);right:-10px;border:5px solid transparent;border-left-color:var(--outer-bg)}
.sl-btn .sl-ico:before{display:block;content:'\e80d';font-family:'Material Icons Round';font-style:normal;line-height:0;font-weight:400}
.rtl .share-a .sl-btn{margin:5px 0 0 10px;transform:rotate3d(0,1,0,180deg)}
.share-a .show-more .btn{background-color:var(--gray-bg);font-size:28px}
.share-a .show-more .btn:before{content:'\e145';font-family:'Material Icons Round';font-weight:400;color:var(--meta-color)}
.share-a li .btn:not(.sl-btn):hover{opacity:.9}
.share-modal{display:flex;flex-direction:column;position:fixed;top:50%;left:50%;width:440px;max-width:calc(100% - 40px);background-color:var(--modal-bg);overflow:hidden;z-index:1010;padding:20px;border-radius:10px;box-shadow:0 1px 2px rgba(0,0,0,0.05),0 5px 15px 0 rgba(0,0,0,0.15);transform:translate(-50%,0);visibility:hidden;opacity:0;transition:all .17s ease}
.modal-header{display:flex;align-items:center;justify-content:space-between;padding:0 0 15px;margin:0 0 20px;border-bottom:1px solid var(--border-color)}
.share-modal .title{font-size:15px;color:var(--title-color);font-weight:700;text-transform:capitalize}
.hide-modal{display:flex;align-items:center;justify-content:center;width:22px;height:22px;background-color:var(--gray-bg);font-size:18px;color:var(--title-color);border-radius:50%}
.hide-modal:before{content:'\e5cd';font-family:'Material Icons Round';font-weight:400}
.hide-modal:hover{color:var(--title-hover-color)}
ul.share-b{display:grid;grid-template-columns:repeat(5,1fr);grid-gap:15px;margin:0 0 20px}
.share-b a{display:flex;align-items:center;justify-content:center;height:38px;background-color:currentColor;font-size:18px}
.share-b .email a{font-size:20px}
.share-b a:before{color:#fff}
.share-b a:hover{opacity:.9}
.copy-link{display:flex;position:relative;width:100%;height:38px;margin:15px 0 0}
.copy-link:before{content:'\e157';font-family:'Material Icons Round';position:absolute;top:50%;left:20px;font-size:20px;color:var(--title-color);line-height:0;transform:translate(-50%,-50%)}
.rtl .copy-link:before{left:unset;right:20px;transform:translate(50%,-50%)}
.copy-link.copied:before{content:'\e877';color:#3fbb50;animation:pbtOn .5s ease}
.copy-link.copied-off:before{animation:pbtOff .5s ease}
.copy-link input{flex:1;width:100%;font-size:14px;color:var(--meta-color);padding:0 15px 0 40px;border:solid var(--border-color);border-width:1px 0 1px 1px;border-radius:var(--radius) 0 0 var(--radius)}
.rtl .copy-link input{padding:0 40px 0 15px;border-width:1px 1px 1px 0;border-radius:0 var(--radius) var(--radius) 0}
.copy-link button{display:flex;align-items:center;justify-content:center;max-width:fit-content;background-color:var(--button-bg);font-size:14px;color:var(--button-color);padding:0 18px;border-radius:0 var(--radius) var(--radius) 0}
.rtl .copy-link button{border-radius:var(--radius) 0 0 var(--radius)}
.copy-link button:hover{opacity:.9}
.share-active .share-modal{transform:translate(-50%,-50%);visibility:visible;opacity:1}
.share-active .hide-modal{transform:rotate(0deg)}
#share-overlay{transition:all .17s ease}
.share-active #share-overlay{visibility:visible;opacity:1}
.p-widget{margin:30px 0 0}
.about-author{display:flex;background-color:var(--gray-bg);padding:20px;border-radius:var(--radius)}
.about-author .author-avatar{width:60px;height:60px;margin:0 15px 0 0;border-radius:50%}
.rtl .about-author .author-avatar{margin:0 0 0 15px}
.about-author .author-title{font-size:18px;color:var(--title-color);font-weight:var(--title-weight);margin:0 0 10px}
.about-author .author-title a{color:var(--title-color)}
.about-author .author-title a:hover{color:var(--title-hover-color)}
.author-description{flex:1}
.author-description .author-text{display:block;font-size:14px;font-weight:400}
.author-description .author-text br,.author-description .author-text a{display:none}
ul.author-links{display:flex;flex-wrap:wrap;padding:0}
.author-links li{margin:10px 12px 0 0}
.rtl .author-links li{margin:10px 0 0 12px}
.author-links li a{display:block;font-size:15px;color:var(--text-color);padding:0}
.author-links li.email a,.author-links li.external-link a{font-size:17px}
.rtl .author-links li.external-link a{transform:rotate3d(0,1,0,180deg)}
.author-links li a:hover{opacity:.9}
#xdfcb-related-posts{display:none}
.related-content .loader{height:180px}
.related-items{display:grid;grid-template-columns:repeat(3,1fr);grid-gap:20px}
.related-items .post{display:flex;flex-direction:column}
.related-items .entry-thumbnail{width:100%;height:140px;margin:0 0 10px}
.related-items .entry-title{font-size:15px}
.related-items .entry-meta{margin:5px 0 0}
.xdfcb-blog-post-comments{display:none;flex-direction:column}
.xdfcb-blog-post-comments.is-visible{display:flex}
.xdfcb-blog-post-comments .fb_iframe_widget_fluid_desktop{float:left;display:block!important;width:calc(100% + 16px)!important;max-width:calc(100% + 16px)!important;margin:0 -8px}
.xdfcb-blog-post-comments .fb_iframe_widget_fluid_desktop span,.xdfcb-blog-post-comments .fb_iframe_widget_fluid_desktop iframe{float:left;display:block!important;width:100%!important}
#disqus_thread,.fb-comments{clear:both;padding:0}
#comments h4#comment-post-message{display:none;float:none}
.comments-title{margin:0}
.has-comments .comments-title.no-message{margin:0 0 5px}
.comments .comment-content{display:block;font-family:var(--text-font);font-size:14px;color:var(--text-color);line-height:1.5em;margin:10px 0 0}
.comments .comment-content > a:hover{text-decoration:underline}
.comment-thread .comment{position:relative;list-style:none;padding:20px;margin:20px 0 0;border:1px solid var(--border-color);border-radius:var(--radius)}
.comment-thread .comment .comment{background-color:var(--gray-bg);padding:20px;border:0;border-radius:var(--radius)}
.comment-thread ol{padding:0;margin:0}
.comment-thread .comment-replies ol{padding:0 0 4px}
.toplevel-thread ol > li:first-child{margin:0}
.toplevel-thread ol > li:first-child > .comment-block{padding-top:0;margin:0;border:0}
.comment-thread ol ol .comment:before{position:absolute;content:'\f060';left:-30px;top:-5px;font-family:'Material Icons Round';font-size:20px;color:var(--border-color);font-weight:400}
.rtl .comment-thread ol ol .comment:before{left:unset;right:-30px;transform:rotate(-180deg)}
.comments .comment-replybox-single iframe{padding:0 0 0 48px;margin:10px 0 -5px}
.rtl .comments .comment-replybox-single iframe{padding:0 48px 0 0}
.comment-thread .avatar-image-container{position:absolute;top:20px;left:20px;width:35px;height:35px;overflow:hidden;border-radius:50%}
.rtl .comment-thread .avatar-image-container{left:auto;right:20px}
.comment-thread .comment .comment .avatar-image-container{left:20px}
.rtl .comment-thread .comment .comment .avatar-image-container{left:unset;right:20px}
.avatar-image-container img{display:block;width:100%;height:100%}
.comments .comment-header{padding:0 0 0 48px}
.rtl .comments .comment-header{padding:0 48px 0 0}
.comments .comment-header .user{display:inline-block;font-family:var(--title-font);font-size:16px;color:var(--title-color);font-weight:var(--title-weight);font-style:normal}
.comments .comment-header .user a{color:var(--title-color)}
.comments .comment-header .user a:hover{color:var(--title-hover-color)}
.comments .comment-header .icon.user{display:none}
.comments .comment-header .icon.blog-author{display:inline-block;font-size:14px;color:var(--main-color);vertical-align:top;margin:-5px 0 0 4px}
.rtl .comments .comment-header .icon.blog-author{margin:-5px 4px 0 0}
.comments .comment-header .icon.blog-author:before{content:'\ef76';font-family:'Material Icons Round';font-weight:400}
.comments .comment-header .datetime{display:block;font-size:12px;font-weight:var(--light-weight);margin:1px 0 0}
.comment-header .datetime a{color:var(--meta-color)}
.comments .comment-actions{display:block;margin:0}
.comments .comment-actions a{display:inline-block;font-size:14px;color:var(--main-color);font-weight:400;font-style:normal;margin:10px 15px 0 0}
.rtl .comments .comment-actions a{margin:10px 0 0 15px}
.comments .comment-actions a:hover{color:var(--main-color);text-decoration:underline}
.item-control{display:none}
.loadmore.loaded a{display:inline-block;border-bottom:1px solid rgba(155,155,155,.51);text-decoration:none;margin-top:15px}
.comments .continue{display:none}
.comments .comment-replies{padding:0 0 0 48px}
.rtl .comments .comment-replies{padding:0 48px 0 0}
.thread-expanded .thread-count a,.loadmore.hidden{display:none}
.comments .footer{float:left;width:100%;font-size:13px;margin:0}
p.comments-message{font-size:14px;color:var(--meta-color);font-style:italic;padding:0 0 20px;margin:15px 0 0}
p.comments-message.no-new-comments{padding:0}
p.comments-message > a{color:var(--main-color)}
p.comments-message > a:hover{color:var(--title-color)}
p.comments-message > em{color:#ff3f34;font-style:normal;margin:0 3px}
#comments[data-embed='false'] p.comments-message > i{color:var(--main-color);font-style:normal}
.comment-form > p{display:none}
.comments #top-ce.comment-replybox-thread,.no-comments .comment-form{padding:15px 20px;margin:20px 0 -5px;border:1px solid var(--border-color);border-radius:var(--radius)}
.no-comments .comment-form{margin-top:0}
.comments #top-continue a{display:flex;align-items:center;justify-content:center;width:100%;height:36px;font-size:14px;color:var(--main-color);font-weight:700;text-transform:uppercase;margin:30px 0 0;border:1px solid var(--border-color);border-radius:var(--radius)}
.comments #top-continue a:hover{color:var(--title-color)}
.post-nav{display:flex;flex-wrap:wrap;justify-content:space-between;font-size:14px;font-weight:var(--light-weight)}
.post-nav > *{display:flex;align-items:center;color:var(--meta-color);margin:0 -4px}
.post-nav a:hover{color:var(--main-color)}
.post-nav span{color:var(--meta-color);cursor:no-drop;opacity:.65}
.post-nav .post-nav-link:before,.post-nav .post-nav-link:after{font-family:'Material Icons Round';font-size:16px;line-height:1;font-weight:400}
.post-nav-newer-link:before,.rtl .post-nav-older-link:after{content:'\e5cb'}
.post-nav-older-link:after,.rtl .post-nav-newer-link:before{content:'\e5cc'}
#blog-pager{display:flex;justify-content:center;margin:30px 0 0}
#blog-pager .load-more{display:flex;align-items:center;justify-content:center;width:100%;height:36px;font-size:14px;color:var(--main-color);font-weight:700;text-transform:uppercase;padding:0 30px;border:1px solid var(--border-color)}
#blog-pager #xdfcb-load-more-link:after{content:'\e5cf';display:inline-block;font-family:'Material Icons Round';font-size:20px;font-weight:400;margin:-1px 0 0}
#blog-pager #xdfcb-load-more-link:hover{color:var(--title-color)}
#blog-pager .no-more.show{display:flex;background:var(--gray-bg);color:var(--meta-color);font-weight:400;cursor:not-allowed;padding:0 25px;border-color:transparent}
#blog-pager .loading,#blog-pager .no-more{display:none}
#blog-pager .loading .loader{height:36px}
#blog-pager .loader:after{width:28px;height:28px}
.sidebar{position:relative;float:left;width:100%;display:grid;grid-template-columns:100%;grid-gap:30px}
.sidebar > .widget{display:flex;flex-direction:column;width:100%}
.sidebar .widget.is-ad > .widget-title{display:none}
.sidebar ul.social-icons{display:grid;grid-template-columns:repeat(2,1fr);grid-gap:10px}
.sidebar .social-icons a{display:flex;align-items:center;gap:10px;width:100%;background-color:currentColor;font-size:18px;font-weight:400;overflow:hidden;padding:8px}
.sidebar .social-icons .rss a,.sidebar .social-icons .email a,.sidebar .social-icons .external-link a{font-size:20px}
.sidebar .social-icons a:before{display:flex;align-items:center;justify-content:center;flex-shrink:0;width:32px;height:28px;background-color:rgba(255,255,255,0.08);color:#fff;border-radius:var(--radius)}
.sidebar .social-icons span{display:-webkit-box;font-size:14px;color:#fff;-webkit-line-clamp:1;-webkit-box-orient:vertical;overflow:hidden}
.sidebar .social-icons .instagram a{background:var(--instagram)}
.sidebar .social-icons a:hover{opacity:.9}
.pbt-s .loader{height:180px}
.popular-items{display:grid;grid-template-columns:1fr;grid-gap:20px}
.popular-items .cs{height:180px}
.popular-items .cs .entry-thumbnail{width:100%;height:100%}
.popular-items .cs .entry-title{font-size:18px}
.popular-items .post:not(.cs){display:flex;gap:15px;padding:15px 0 0;border-top:1px solid var(--border-color)}
.popular-items .post.item-1{padding:0;border:0}
.popular-items .entry-index{font-size:54px;color:var(--title-color);line-height:.85em;opacity:.1}
.popular-items .post:not(.cs) .entry-header{flex:1}
.popular-items .post:not(.cs) .entry-title{font-size:14px}
.default-items{display:grid;grid-template-columns:1fr;grid-gap:20px}
.default-items .post{display:flex;gap:13px}
.default-items .entry-thumbnail{width:110px;height:70px}
.default-items .entry-header{flex:1}
.default-items .entry-title{font-size:14px}
.cmm1-items{display:grid;grid-template-columns:1fr;grid-gap:25px}
.cmm1-items .entry-inner{display:flex;gap:13px}
.cmm1-items .entry-thumbnail{width:45px;height:45px;z-index:1;border-radius:50%}
.cmm1-items .entry-header{flex:1}
.cmm1-items .entry-title{font-size:14px}
.cmm1-items .entry-inner:hover .entry-title{color:var(--title-hover-color)}
.cmm1-items .cmm-snippet{font-size:13px;line-height:1.3em;margin:4px 0 0}
.FeaturedPost .post{height:180px}
.FeaturedPost .post .entry-thumbnail{width:100%;height:100%}
.FeaturedPost .post .entry-title{font-size:18px}
.list-style li{font-size:14px}
.list-style li a,.text-list li{display:block;color:var(--title-color);padding:8px 0}
.list-style li a.has-count{display:flex;justify-content:space-between}
.list-style li:first-child a,.text-list li:first-child{padding:0 0 8px}
.list-style li:last-child a,.text-list li:last-child{padding:8px 0 0}
.list-style li a:hover{color:var(--title-hover-color)}
.list-style .count-style{display:inline-block;color:var(--meta-color)}
.cloud-label ul{display:flex;flex-wrap:wrap;margin:-4px 0 0}
.cloud-label li{margin:4px 4px 0 0}
.rtl .cloud-label li{margin:4px 0 0 4px}
.cloud-label li a{display:flex;height:28px;background-color:var(--gray-bg);color:var(--title-color);font-size:14px;font-weight:400;align-items:center;padding:0 12px}
.cloud-label li a:hover{color:var(--title-hover-color)}
.cloud-label .label-count{display:inline-block;margin:0 0 0 4px}
.rtl .cloud-label .label-count{margin:0 4px 0 0}
.BlogSearch .search-form{display:flex}
.BlogSearch .search-input{width:100%;flex:1;height:36px;font-size:14px;color:var(--text-color);padding:0 10px;border:solid var(--border-color);border-width:1px 0 1px 1px;border-radius:var(--radius) 0 0 var(--radius)}
.rtl .BlogSearch .search-input{border-width:1px 1px 1px 0;border-radius:0 var(--radius) var(--radius) 0}
.BlogSearch .search-input::placeholder{color:var(--text-color);opacity:.65}
.BlogSearch .search-input:focus{border-color:var(--button-bg)}
.BlogSearch .search-action{height:36px;background-color:var(--button-bg);font-size:14px;color:var(--button-color);cursor:pointer;padding:0 15px;border-radius:0 var(--radius) var(--radius) 0}
.rtl .BlogSearch .search-action{border-radius:var(--radius) 0 0 var(--radius)}
.BlogSearch .search-action:hover{opacity:.9}
.MailChimp.widget{border-top:5px solid var(--button-bg)}
.MailChimp .widget-content{padding:20px;box-shadow:0 2px 8px rgba(0,0,0,0.10)}
.MailChimp .mailchimp-title{font-size:22px;color:var(--title-color);margin:0 0 15px}
.MailChimp .mailchimp-text{font-size:14px;margin:0 0 15px}
.MailChimp form{display:flex}
.MailChimp .mailchimp-email-address{flex:1;width:100%;height:38px;font-size:14px;color:var(--text-color);padding:0 10px;border:solid var(--border-color);border-width:1px 0 1px 1px;border-radius:var(--radius) 0 0 var(--radius)}
.rtl .MailChimp .mailchimp-email-address{border-width:1px 1px 1px 0;border-radius:0 var(--radius) var(--radius) 0}
.MailChimp .mailchimp-email-address::placeholder{color:var(--text-color);opacity:.65}
.MailChimp .mailchimp-email-address:focus{border-color:var(--button-bg)}
.MailChimp .mailchimp-submit{width:100%;max-width:fit-content;height:38px;background-color:var(--button-bg);font-size:14px;color:var(--button-color);font-weight:400;cursor:pointer;padding:0 10px;border-radius:0 var(--radius) var(--radius) 0}
.rtl .MailChimp .mailchimp-submit{border-radius:var(--radius) 0 0 var(--radius)}
.MailChimp .mailchimp-submit:hover{opacity:.9}
.Profile ul li{float:left;width:100%;padding:20px 0 0;margin:20px 0 0;border-top:1px solid var(--border-color)}
.Profile ul li:first-child{padding:0;margin:0;border:0}
.Profile .individual,.Profile .team-member{display:flex;align-items:center}
.Profile .profile-img{width:45px;height:45px;background-color:var(--gray-bg);overflow:hidden;color:transparent!important;margin:0 13px 0 0;border-radius:50%}
.rtl .Profile .profile-img{margin:0 0 0 13px}
.Profile .profile-info{flex:1}
.Profile .profile-name{display:block;font-family:var(--title-font);font-size:15px;color:var(--title-color);font-weight:var(--title-weight)}
.Profile .profile-name:hover{color:var(--title-hover-color)}
.Profile .profile-link{display:block;font-size:12px;color:var(--meta-color)}
.Profile .profile-link:hover{color:var(--main-color)}
.Text .widget-content{font-family:var(--text-font);font-size:14px;color:var(--text-color)}
.Image .image-caption{font-family:var(--text-font);font-size:14px;margin:6px 0 0}
.contact-form-widget .cf-s{float:left;width:100%;height:36px;font-size:14px;color:var(--text-color);padding:0 10px;margin:0 0 10px;border:1px solid var(--border-color);border-radius:var(--radius)}
.contact-form-email-message.cf-s{float:left;width:100%;height:auto;resize:vertical;padding:10px}
.contact-form-widget .cf-s::placeholder{color:var(--text-color);opacity:.9}
.contact-form-widget .cf-s:focus{border-color:var(--button-bg)}
.contact-form-button-submit{float:left;width:100%;height:36px;background-color:var(--button-bg);font-family:inherit;font-size:14px;color:var(--button-color);font-weight:400;cursor:pointer;padding:0 20px;border:0;border-radius:var(--radius)}
.contact-form-button-submit:hover{opacity:.9}
.contact-form-widget p{margin:0}
.contact-form-widget .contact-form-error-message-with-border,.contact-form-widget .contact-form-success-message-with-border{float:left;width:100%;background-color:rgba(0,0,0,0);font-size:13px;color:#e74c3c;text-align:left;line-height:1;margin:10px 0 0;border:0}
.contact-form-widget .contact-form-success-message-with-border{color:#27ae60}
.rtl .contact-form-error-message-with-border,.rtl .contact-form-success-message-with-border{text-align:right}
.contact-form-cross{cursor:pointer;margin:0 0 0 3px}
.rtl .contact-form-cross{margin:0 3px 0 0}
.Attribution a{display:flex;align-items:center;font-size:14px;color:var(--title-color);font-weight:var(--title-weight)}
.Attribution a > svg{width:16px;height:16px;fill:var(--main-color);margin:0 4px 0 0}
.rtl .Attribution a > svg{margin:0 0 0 4px}
.Attribution a:hover{color:var(--title-hover-color)}
.Attribution .copyright{font-size:12px;color:var(--meta-color);padding:0 20px;margin:2px 0 0}
#google_translate_element{position:relative;overflow:hidden}
.Stats .text-counter-wrapper{display:flex;align-items:center;font-size:18px;color:var(--meta-color);font-weight:700;text-transform:uppercase;line-height:1;margin:0}
.Stats .text-counter-wrapper:before{content:'\e202';font-family:'Material Icons Round';font-size:22px;color:var(--title-color);font-weight:400;margin:0 4px 0 0}
.rtl .Stats .text-counter-wrapper:before{margin:0 0 0 4px}
.ReportAbuse > h3{display:flex;font-size:14px;font-weight:400}
.ReportAbuse > h3:before{content:'\e002';font-family:'Material Icons Round';font-size:18px;color:var(--main-color);margin:0 3px 0 0}
.rtl .ReportAbuse > h3:before{margin:0 0 0 3px}
.ReportAbuse > h3 a:hover{text-decoration:underline}
#footer-wrapper{position:relative;float:left;width:100%;background-color:var(--footer-bg);box-shadow:0 2px 8px rgba(0,0,0,0.10)}
.primary-footer{--title-color:var(--footer-color);--title-hover-color:var(--footer-hover-color);--meta-color:var(--footer-meta-color);--text-color:var(--footer-text-color);--border-color:var(--footer-border)}
.primary-footer.has-border .container{border-bottom:1px solid var(--border-color)}
#xdfcb-about-section{flex-wrap:wrap;padding:40px 0}
.about-section .Image{display:flex;justify-content:space-between;align-items:center;width:calc(100% - $(sidebar.width + 30px))}
.footer-info{flex:1}
.footer-info .title{font-size:15px;color:var(--title-color);text-transform:uppercase;margin:0 0 10px}
.footer-logo{padding:0 30px 0 0}
.rtl .footer-logo{padding:0 0 0 30px}
.footer-logo img{display:block;width:auto;height:auto;max-height:40px}
.footer-info .image-caption{font-size:15px;margin:0}
.footer-info .image-caption a{color:var(--title-color)}
.footer-info .image-caption a:hover{opacity:.9}
.about-section .LinkList{width:$(sidebar.width);display:flex;align-items:center;justify-content:flex-end;margin:0}
.about-section ul.social-icons{display:flex;flex-wrap:wrap}
.about-section .social-icons li{margin:0 0 0 10px}
.rtl .about-section .social-icons li{margin:0 10px 0 0}
.about-section .social-icons a{display:flex;align-items:center;justify-content:center;width:36px;height:36px;background-color:var(--gray-bg);font-size:16px}
.about-section .social-icons .rss a,.about-section .social-icons .email a,.about-section .social-icons .external-link a{font-size:20px}
.about-section .social-icons a:before{color:var(--title-color)}
.about-section .social-icons a:hover{background-color:currentColor}
.about-section .social-icons a:hover:before{color:#fff}
.about-section .social-icons .instagram a:hover{background:var(--instagram)}
.about-section .social-error{height:34px;background-color:var(--gray-bg);color:var(--title-color);padding:0 10px;border-radius:var(--radius)}
.footer-bar{background-color:var(--footerbar-bg);color:var(--footerbar-color);padding:20px 0}
.footer-bar .footer-copyright{font-size:14px;font-weight:400;margin:0}
.footer-bar .footer-copyright a{color:var(--footerbar-color)}
.footer-bar .footer-copyright a:hover{color:var(--footerbar-hover-color)}
#footer-menu{position:relative;display:block;margin:0}
.footer-menu ul{display:flex;flex-wrap:wrap}
.footer-menu ul li a{font-size:14px;color:var(--footerbar-color);padding:0;margin:0 0 0 25px}
.rtl .footer-menu ul li a{margin:0 25px 0 0}
#footer-menu ul li a:hover{color:var(--footerbar-hover-color)}
.is-error #main-wrapper{width:100%}
.is-error #sidebar-wrapper{display:none}
.errorWrap{color:var(--title-color);text-align:center;padding:60px 0}
.errorWrap h3{font-size:160px;color:var(--title-color);line-height:1;margin:0 0 25px}
.errorWrap h4{font-size:27px;color:var(--title-color);margin:0 0 25px}
.errorWrap p{color:var(--text-color);font-size:15px;margin:0 0 15px}
.errorWrap a{display:inline-block;height:36px;background-color:var(--button-bg);font-size:14px;color:var(--button-color);line-height:36px;padding:0 30px;margin:15px 0 0}
.errorWrap a:hover{opacity:.9}
#back-top{display:flex;align-items:center;justify-content:center;position:fixed;bottom:20px;right:20px;width:36px;height:36px;background-color:var(--button-bg);font-size:24px;color:var(--button-color);z-index:50;opacity:0;visibility:hidden;transition:visibility .17s ease,opacity .17s ease}
.rtl #back-top{right:auto;left:20px}
#back-top:before{content:'\e5ce';font-family:'Material Icons Round';font-weight:400}
#back-top.show{opacity:1;visibility:visible}
#back-top:hover{opacity:.9}
ins.adsbygoogle-noablate[data-anchor-shown="true"]{z-index:990!important}
#content-wrapper > .google-auto-placed,#content-wrapper .container > .google-auto-placed{display:none!important}
#hidden-widgets{display:none;visibility:hidden}
.CSS_LIGHTBOX{z-index:999999!important}
.CSS_LIGHTBOX_BG_MASK{background-color:rgba(0,0,0,0.9)!important;opacity:1!important;backdrop-filter:blur(1px)}
.CSS_LIGHTBOX_BTN_CLOSE{background:transparent!important;top:10px!important;right:15px!important}
.CSS_LIGHTBOX_BTN_CLOSE:before{content:'\e5cd';font-family:'Material Icons Round';color:#fff;font-size:24px;font-weight:400}
.CSS_LIGHTBOX_BTN_CLOSE:hover:before{opacity:.85}
.rtl .CSS_LIGHTBOX_BTN_CLOSE{right:unset!important;left:15px}
.CSS_LIGHTBOX_ATTRIBUTION_INDEX_CONTAINER .CSS_HCONT_CHILDREN_HOLDER > .CSS_LAYOUT_COMPONENT.CSS_HCONT_CHILD:first-child > .CSS_LAYOUT_COMPONENT{opacity:0}
.pbt-ad{display:block;text-align:center;line-height:0}
@media only screen and (max-width: $(row.width + 60px)) {
#outer-wrapper,.is-boxed #outer-wrapper,.is-boxed .header-header{width:100%;max-width:100%;margin:0}
.row-x1,.row-x2{width:100%}
.main-header .container,.headerbar-wrap .container,#content-wrapper .container,#footer-wrapper .container{padding:0 20px}
#main-wrapper{width:calc(70% - 30px)}
#sidebar-wrapper{width:30%}
}
@media only screen and (max-width: 980px) {
.main-header .container{padding:0}
.header-items{flex-wrap:nowrap}
.mobile-menu-toggle{display:flex}
#xdfcb-main-menu{display:none}
#slide-menu{display:block}
.nav-active #overlay{visibility:visible;opacity:1}
.flex-left{overflow:hidden;transition:all .17s ease}
.main-logo{flex-shrink:1}
.flex-right{padding:0 0 0 10px}
.rtl .flex-right{padding:0 10px 0 0}
.flex-right,.rtl .flex-right{position:relative;top:unset;left:unset;right:unset}
.search-toggle{width:auto;background-color:transparent;font-size:26px;padding:0 16px 0 11px}
.rtl .search-toggle{padding:0 11px 0 16px}
.main-search{width:100%;background:var(--header-bg);padding:0 0 0 20px}
.rtl .main-search{padding:0 20px 0 0}
.main-search .search-form{background-color:transparent;border-radius:0;box-shadow:none;--search-color:var(--header-color);--search-close:var(--header-color)}
.main-search .search-input{padding:0}
.main-search .search-toggle:hover{color:var(--header-hover-color);opacity:1}
.search-active .flex-left{visibility:hidden;opacity:0}
.headerbar-wrap .container{padding:0}
.hb-menu ul{white-space:nowrap}
.hb-menu:before,.hb-menu:after{opacity:1}
.hb-menu:before{left:0}
.rtl .hb-menu:after{right:0}
.hb-menu ul:before,.hb-menu ul:after{content:'';display:inline-block;width:20px;height:auto;flex-shrink:0;margin:0}
.social-toggle,.hb-icons{display:none}
}
@media only screen and (max-width: 880px) {
#content-wrapper > .container,.is-left #content-wrapper > .container{flex-direction:column!important;justify-content:flex-start}
#main-wrapper,#sidebar-wrapper{width:100%}
#sidebar-wrapper{margin:30px 0 0}
#xdfcb-about-section{flex-wrap:wrap;flex-direction:column}
.about-section .Image{width:100%;flex-direction:column;justify-content:center;text-align:center}
.footer-info{text-align:center;margin:25px 0 0}
.footer-info .title{display:none}
.footer-logo{padding:0!important}
.about-section .LinkList{width:100%;justify-content:center;margin:20px 0 0}
.about-section ul.social-icons{justify-content:center}
.about-section .social-icons li{margin:10px 5px 0!important}
.footer-bar{height:auto;line-height:inherit;padding:25px 0}
.footer-bar .container{flex-direction:column-reverse;justify-content:center}
.footer-bar .footer-copyright,#footer-menu{width:100%;text-align:center}
#footer-menu{padding:0 0 10px}
.footer-menu ul{justify-content:center}
.footer-menu ul li a{display:block;margin:0 10px 5px!important}
.nav-active #back-top{opacity:0!important}
}
@media only screen and (max-width: 680px) {
.list-items .post{flex-direction:column;border:0}
.list-items .entry-thumbnail{width:100%;max-width:100%;height:200px;margin:0 0 16px}
.list-items .entry-header{flex:unset;padding:0!important}
.list-items .entry-excerpt{display:-webkit-box;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical;margin:8px 0 0}
.list-items .entry-meta{margin:8px 0 0}
.grid-items{grid-template-columns:1fr}
.grid-items .entry-thumbnail{height:200px}
.grid-items .entry-title{font-size:19px}
.grid-items .entry-excerpt{margin:8px 0 0}
.grid-items .entry-meta{margin:8px 0 0}
#breadcrumb{margin:0 0 13px}
.item-post h1.entry-title{font-size:33px}
.post-body table{display:block}
.author-description .author-text,.comments .comment-content{font-size:$(itempost.content.size)}
.related-items{grid-template-columns:repeat(2,1fr)}
.related-items .entry-thumbnail{height:130px}
.popular-items .cs{height:200px}
.FeaturedPost .post{height:200px}
.errorWrap{padding:20px 0 30px}
.errorWrap h3{font-size:130px}
.errorWrap h4{line-height:initial}
}
@media only screen and (max-width: 540px) {
.item-post h1.entry-title{font-size:27px}
.p-eh .entry-meta .has-time .entry-avatar{flex-shrink:0;width:40px;height:40px;margin:0 7px 0 0}
.rtl .p-eh .entry-meta .has-time .entry-avatar{margin:0 0 0 7px}
.p-eh .entry-meta .al-items{flex-direction:column;line-height:1;padding:0 15px 0 0}
.rtl .p-eh .entry-meta .al-items{padding:0 0 0 15px}
.p-eh .entry-meta .al-items .by{color:var(--title-color)}
.p-eh .entry-meta .al-items .entry-time{font-size:13px;margin:4px 0 0}
.p-eh .entry-meta .al-items .entry-time .sp{display:none}
.share-a .twitter .btn{width:36px}
.share-a .twitter .btn:before{width:100%;background-color:transparent}
.share-a .twitter .btn span{display:none}
.related-items .entry-thumbnail{height:120px}
.related-items .entry-title{font-size:14px}
}
@media only screen and (max-width: 380px) {
.list-items .entry-thumbnail{height:180px}
.grid-items .entry-thumbnail{height:180px}
.item-post h1.entry-title{font-size:25px}
.share-a .facebook .btn{width:36px}
.share-a .facebook .btn:before{width:100%;background-color:transparent}
.share-a .facebook .btn span{display:none}
.related-items .entry-thumbnail{height:95px}
.popular-items .cs{height:180px}
.FeaturedPost .post{height:180px}
}
@media only screen and (max-width: 340px) {
ul.share-b{grid-gap:10px}
#slide-menu{width:100%}
.errorWrap h3{font-size:110px}
.errorWrap h4{font-size:27px}
}
]]></b:skin>
</b:if>
<b:if cond='data:view.isLayoutMode'>
<b:template-skin><![CDATA[
html,body#layout #outer-wrapper,body#layout .row{width:auto;padding:0}
body#layout{position:relative;width:auto;max-width:100%;background-color:#fff;padding:95px 5px 0;margin:0 0 0 1px;border-width:1px 0 0;border-color:#eceff1}
body#layout:before{content:'TechSpot - v1.0.0';position:absolute;top:0;left:5px;right:5px;height:95px;font-family:Roboto,sans-serif;font-size:23px;color:#263238;line-height:95px;text-align:center}
body#layout div.section{display:block;background-color:#eceff1!important;margin:0 5px 10px!important;padding:16px 16px 18px!important;border:0}
body#layout .no-items.section{display:block}
body#layout .section h4{font-size:14px;color:#263238;text-transform:uppercase;margin:0}
body#layout .section h4:after{text-transform:initial;color:#757575;font-weight:400}
body#layout .add_widget a{color:#4385f5!important}
body#layout .widget-wrap3{overflow:hidden}
body#layout .widget-content{width:auto;max-width:none;max-height:none;margin:0;border:1px solid #e7e7e8;border-left:0}
body#layout .locked-widget .widget-content{border-left:1px solid #4385f5}
body#layout .locked-widget .widget-content:hover{border-left-color:#33a453}
body#layout div.layout-title{color:#757575}
body#layout .widget .widget-content a.editlink{border-radius:2px}
body#layout .visibility .editlink{background:#4385f5 url(https://1.bp.blogspot.com/--z1wepFalfQ/YOObl8avCFI/AAAAAAAAAE8/Z-iC0j0LLpo7u2ZpHvW0hGaHhBOvVYYaQCLcBGAsYHQ/s48/edit.png) no-repeat center!important;background-size:20px!important}
body#layout .visibility .editlink:hover{background-color:#33a453!important}
body#layout .draggable-widget .widget-wrap2{background:#4385f5 url(https://1.bp.blogspot.com/-ciJD7MVmo10/YORQlzt9a1I/AAAAAAAAAFk/L4fK5cgelFoWX9rZvGFKZdr1d_RM9kfjACLcBGAsYHQ/s68/drag.png) no-repeat 4px 50%!important;background-size:4px auto!important}
body#layout .draggable-widget .widget-wrap1:hover .widget-wrap2{background-color:#33a453!important}
body#layout .visibility .layout-widget-state.visible{background-image:url(https://1.bp.blogspot.com/-aPoC3YxQo6g/YOOeDVSsJqI/AAAAAAAAAFM/oyvPLSJVIRQpAu-g0gZL89g5Caq4_4DeQCLcBGAsYHQ/s48/visibility_on.png)!important;background-size:24px!important}
body#layout .visibility .layout-widget-state.not-visible{background-image:url(https://1.bp.blogspot.com/-x_kkTMRQfHs/YOOeMUjTE8I/AAAAAAAAAFQ/RRj6YLBNuMEHwTB_81304fCxy8dl7h46gCLcBGAsYHQ/s48/visibility_off.png)!important;background-size:24px!important;opacity:1}
body#layout div.layout-widget-description{display:none;font-size:11px;line-height:1.2em}
body#layout #theme-options,body#layout #main-menu .widget{display:block!important}
body#layout div.pbt-panel{background-color:rgba(67,133,245,0.15)!important;overflow:hidden!important}
body#layout .pbt-panel .widget{float:left;width:49.5%;margin-right:1%}
body#layout .pbt-panel .widget-content{border-color:#d5e3fc!important}
body#layout .pbt-panel .HTML{margin-right:0}
body#layout .pbt-panel div.layout-widget-description,body#layout .mobile-menu-toggle,body#layout .flex-right,body#layout .main-search{display:none}
body#layout #headerbar{overflow:hidden!important}
body#layout #headerbar .widget{float:left;width:49.5%;margin-right:1%}
body#layout #headerbar #LinkList202{margin-right:0}
body#layout .flex-left{display:flex}
body#layout .main-logo,body#layout .xdfcb-main-menu{width:50%}
body#layout #content-wrapper{padding:0;margin:0}
body#layout #content-wrapper > .container{display:flex;margin:0}
body#layout #main-wrapper{width:67%;padding:0}
body#layout #sidebar-wrapper{width:33%;padding:0}
body#layout #xdfcb-about-section{overflow:hidden!important}
body#layout #xdfcb-about-section .widget{float:left;width:49.5%;margin-right:1%}
body#layout #xdfcb-about-section .LinkList{margin-right:0}
body#layout .footer-bar .container{display:flex}
body#layout #footer-menu,body#layout #footer-copyright{width:50%}
body#layout .section > h4:after{font-size:12px}
body#layout #pbt-panel > h4:after{content:' - Default Thumbnail, Date Format, Translate Months and More'}
body#layout #main-logo > h4:after{content:' - Main Logo and Dark Logo'}
body#layout #xdfcb-main-menu > h4:after{content:' - Menu Links and Sub Links'}
body#layout #headerbar > h4:after{content:' - Custom Links and Social Links'}
body#layout #featured > h4:after{content:' - by Featured Post Gadget'}
body#layout #main > h4:after{content:' - Default Blog Posts, AdSense In-Feed, Comments and More'}
body#layout #xdfcb-related-posts > h4:after{content:' - Exclusive Non-Duplicate Post System'}
body#layout #sidebar > h4:after{content:' - Default Gadgets'}
body#layout #xdfcb-about-section > h4:after{content:' - Site Logo, Description and Social Icons'}
body#layout #footer-copyright > h4:after{content:' - Custom Credits'}
body#layout #footer-menu > h4:after{content:' - Footer Links'}
body#layout:after{content:'Design by - ProBloggerTemplates.com';display:block;font-family:Roboto,sans-serif;font-size:14px;color:rgba(0,0,0,0.54);line-height:1;text-align:center;visibility:visible;padding:20px 0 30px}
body#layout #hidden-widgets{display:none!important}
]]></b:template-skin>
</b:if>
<b:if cond='data:widgets.AdSense.first or data:blog.adsenseClientId'>
  <!-- Google AdSense -->
  <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
  <meta content='vfH1AViTM_9vzNb81baYxfqMq4n62HxbF2reOFw9ERc' name='google-site-verification'/>
</b:if>
<b:if cond='data:blog.analyticsAccountNumber'>
  <!-- Google Analytics -->
  <b:include data='blog' name='google-analytics'/>
</b:if>
<b:defaultmarkups>
  <b:defaultmarkup type='Common'>
    <b:includable id='customOpenGraphMetaData'>
      <!-- Open Graph Meta Tags -->
      <meta expr:content='data:blog.localeUnderscoreDelimited' property='og:locale'/>
      <b:if cond='data:view.isHomepage'>
        <meta content='website' property='og:type'/>
        <b:elseif cond='data:view.isSingleItem'/>
        <meta content='article' property='og:type'/>
        <b:elseif cond='data:view.isMultipleItems and not data:view.isHomepage'/>
        <meta content='object' property='og:type'/>
      </b:if>
      <meta expr:content='data:view.title.escaped' property='og:title'/>
      <meta expr:content='data:blog.title.escaped' property='og:site_name'/>
      <meta expr:content='data:view.description.escaped' property='og:description'/>
      <meta expr:content='data:blog.url.canonical' property='og:url'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:content='data:widgets.Blog.first.posts[0].featuredImage resizeImage 1600' name='meta' property='og:image'/>
      <b:tag cond='data:view.featuredImage' expr:content='data:view.featuredImage resizeImage 1600' name='meta' property='og:image'/>
      <!-- Twitter Meta Tags -->
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:view.title.escaped' name='twitter:title'/>
      <meta expr:content='data:view.description.escaped' name='twitter:description'/>
      <meta expr:content='data:blog.url.canonical' name='twitter:domain'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:content='data:widgets.Blog.first.posts[0].featuredImage resizeImage 1600' name='meta' property='twitter:image'/>
      <b:tag cond='data:view.featuredImage' expr:content='data:view.featuredImage resizeImage 1600' name='meta' property='twitter:image'/>
    </b:includable>
    <b:includable id='theme-head'>
      <meta expr:content='&quot;text/html; charset=&quot; + data:blog.encoding' http-equiv='Content-Type'/>
      <meta content='width=device-width, initial-scale=1, minimum-scale=1, user-scalable=yes' name='viewport'/>
      <!-- DNS Prefetch -->
      <link href='//fonts.googleapis.com' rel='dns-prefetch'/>
      <link href='//fonts.gstatic.com' rel='dns-prefetch'/>
      <link href='//dnjs.cloudflare.com' rel='dns-prefetch'/>
      <link href='//1.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//2.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//3.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//4.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//blogger.googleusercontent.com' rel='dns-prefetch'/>
      <link href='//lh5.googleusercontent.com' rel='dns-prefetch'/>
      <link href='//www.blogger.com' rel='dns-prefetch'/>
      <!-- Site Info -->
      <meta content='blogger' name='generator'/>
      <title><data:view.title.escaped/></title>
      <meta expr:content='data:view.description.escaped' name='description'/>
      <link expr:href='data:view.url.canonical' rel='canonical'/>
      <b:if cond='data:blog.adultContent'>
        <meta content='adult' name='rating'/>
      </b:if>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
      <meta expr:content='data:skin.vars.main_color' name='theme-color'/>
      <b:include name='customOpenGraphMetaData'/>
      <!-- Feed Links -->
      <data:blog.feedLinks/><data:blog.meTag/>
      <b:if cond='data:view.isHomepage'>
        <!-- Schema Markup -->
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
      </b:if>
      <!-- Styles and Scripts -->
      <b:tag href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/fontawesome.min.css' name='link' rel='stylesheet'/>
      <b:tag cond='data:blog.languageDirection == &quot;rtl&quot;' href='https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700&amp;display=swap' name='link' rel='stylesheet'/>
    </b:includable>
    <b:includable id='theme-body-class'>
      <b:class cond='data:view.isHomepage' name='is-home'/>
      <b:class cond='data:view.isMultipleItems' name='is-multiple'/>
      <b:class cond='data:view.isSingleItem' name='is-single'/>
      <b:class cond='data:view.isPage' name='is-page'/>
      <b:class cond='data:view.isPost' name='is-post'/>
      <b:class cond='data:view.isError' name='is-multiple is-error'/>
      <b:class cond='data:blog.isMobileRequest' name='is-mobile'/>
      <b:class cond='data:skin.vars.boxed == &quot;1px&quot;' name='is-boxed'/>
      <b:class cond='data:skin.vars.sidebar == &quot;1px&quot;' name='is-left'/>
    </b:includable>
    <b:includable id='theme-custom-lang'>
      <b:switch var='data:message'>
        <b:case value='prevPost'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Previous Post<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Artículo Anterior<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Postagem Anterior<b:else/><data:messages.newer/></b:if>
        <b:case value='nextPost'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Next Post<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Artículo Siguiente<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Próxima Postagem<b:else/><data:messages.older/></b:if>
        <b:case value='loadMorePosts'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Load More<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Carga Más<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Carregar Mais<b:elseif cond='data:blog.locale.language == &quot;ar&quot;'/>تحميل المزيد<b:else/><data:messages.loadMorePosts/></b:if>
      </b:switch>
    </b:includable>
    <b:includable id='widget-title'>
      <b:if cond='data:title == &quot;{ads}&quot;'>
        <b:class name='is-ad'/>
        <b:elseif cond='data:widget.type == &quot;AdSense&quot;'/>
        <b:class name='is-ad'/>
      </b:if>
      <b:if cond='data:widget.type == &quot;HTML&quot; and data:title contains &quot;getMailchimp&quot;'>
        <b:class name='MailChimp'/>
      </b:if>
      <b:if cond='data:defaultTitle or data:title'>
        <b:if cond='data:title != &quot;{ads}&quot; and not (data:widget.type == &quot;HTML&quot; and data:title contains &quot;getMailchimp&quot;)'>
          <b:if cond='data:widget.sectionId not in [&quot;pbt-panel&quot;,&quot;main-logo&quot;,&quot;xdfcb-main-menu&quot;,&quot;headerbar&quot;,&quot;xdfcb-about-section&quot;,&quot;footer-copyright&quot;,&quot;footer-menu&quot;]'>
            <div expr:class='data:widget.sectionId in [&quot;sidebar&quot;] ? &quot;title-wrap widget-title&quot; : &quot;widget-title&quot;'><h3 class='title'><data:title/></h3></div>
          </b:if>
        </b:if>
      </b:if>
    </b:includable>
    <b:includable id='pagelist-content'>
      <div class='widget-content'>
        <ul class='link-list list-style'>
          <b:loop values='data:links' var='link'>
            <li><a expr:href='data:link.href'><data:link.title/></a></li>
          </b:loop>
        </ul>
      </div>
    </b:includable>
    <b:includable id='linklist-content'>
      <b:if cond='data:widget.sectionId in [&quot;headerbar&quot;]'>
        <b:class expr:name='data:widget.instanceId == &quot;LinkList201&quot; ? &quot;hb-menu&quot; : &quot;hb-icons&quot;'/> 
      </b:if>
      <b:if cond='data:widget.sectionId in [&quot;headerbar&quot;,&quot;sidebar&quot;,&quot;fc-1&quot;,&quot;fc-2&quot;,&quot;fc-3&quot;,&quot;xdfcb-about-section&quot;]'>
        <b:tag class='widget-content' cond='data:widget.sectionId not in [&quot;headerbar&quot;,&quot;xdfcb-about-section&quot;]' name='div'>
          <b:if cond='data:links any l =&gt; l.name contains &quot;getSocial&quot;'>
            <b:if cond='(data:widget.sectionId == &quot;headerbar&quot;)'>
              <b:if cond='data:widget.instanceId == &quot;LinkList202&quot;'>
                <ul class='social-icons social color'>
                  <b:loop values='data:links' var='link'>
                    <b:if cond='!(data:link.name contains &quot;getSocial&quot;)'>
                      <li expr:class='data:link.name'><a data-text='true' expr:alt='data:link.name' expr:class='&quot;fa-&quot; + data:link.name' expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'/></li>
                    </b:if>
                  </b:loop>
                </ul>
                <b:else/>
                <b:with value='data:widgets.LinkList filter (w =&gt; w.id == &quot;LinkList201&quot;) map (w =&gt; w.title)' var='pbtTitle'>
                  <ul class='link-list'>
                    <b:if cond='data:pbtTitle.first'><li class='title item-0'><span><data:pbtTitle.first/></span></li></b:if>
                    <b:loop index='i' values='data:links' var='link'>
                      <li expr:class='data:pbtTitle.first ? &quot;item-&quot; + (data:i + 1) : &quot;item-&quot; + data:i'><a expr:href='data:link.target'><data:link.name/></a></li>
                    </b:loop>
                  </ul>
                </b:with>
              </b:if>
              <b:elseif cond='data:widget.sectionId == &quot;sidebar&quot;'/>
              <ul class='social-icons social color'>
                <b:loop values='data:links' var='link'>
                  <b:if cond='!(data:link.name contains &quot;getSocial&quot;)'>
                    <li expr:class='data:link.name'><a data-text='true' expr:alt='data:link.name' expr:class='&quot;fa-&quot; + data:link.name + &quot; btn&quot;' expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'/></li>
                  </b:if>
                </b:loop>
              </ul>
              <b:else/>
              <ul class='social-icons social color'>
                <b:loop values='data:links' var='link'>
                  <b:if cond='!(data:link.name contains &quot;getSocial&quot;)'>
                    <li expr:class='data:link.name'><a expr:alt='data:link.name' expr:class='&quot;fa-&quot; + data:link.name + &quot; btn&quot;' expr:href='data:link.target' expr:title='data:link.name' rel='nofollow noopener' target='_blank'/></li>
                  </b:if>
                </b:loop>
              </ul>
            </b:if>
            <b:else/>
            <b:if cond='data:widget.instanceId in [&quot;LinkList202&quot;,&quot;LinkList203&quot;]'>
              <span class='social-error'>Shortcode Required</span>
              <b:else/>
              <b:with value='data:widgets.LinkList filter (w =&gt; w.id == &quot;LinkList201&quot;) map (w =&gt; w.title)' var='pbtTitle'>
                <ul expr:class='data:widget.sectionId == &quot;headerbar&quot; ? &quot;link-list&quot; : &quot;link-list list-style&quot;'>
                  <b:if cond='data:pbtTitle.first and (data:widget.sectionId == &quot;headerbar&quot;) and (data:widget.instanceId != &quot;LinkList202&quot;)'><li class='title item-0'><span><data:pbtTitle.first/></span></li></b:if>
                  <b:loop index='i' values='data:links' var='link'>
                    <b:if cond='(data:widget.sectionId == &quot;headerbar&quot;) and (data:widget.instanceId == &quot;LinkList201&quot;)'>
                      <li expr:class='data:pbtTitle.first ? &quot;item-&quot; + (data:i + 1) : &quot;item-&quot; + data:i'><a expr:href='data:link.target'><data:link.name/></a></li>
                      <b:else/>
                      <li><a expr:href='data:link.target'><data:link.name/></a></li>
                    </b:if>
                  </b:loop>
                </ul>
              </b:with>
            </b:if>
          </b:if>
        </b:tag>
        <b:elseif cond='data:widget.sectionId == &quot;xdfcb-main-menu&quot;'/>
        <ul class='main-nav' id='main-nav'>
          <b:loop index='i' values='data:links' var='link'>
            <li expr:id='&quot;item-&quot; + data:i'><a expr:href='data:link.target'><data:link.name/></a></li>
          </b:loop>
        </ul>
        <b:else/>
        <b:tag class='widget-content' cond='data:widget.sectionId not in [&quot;footer-menu&quot;]' name='div'>
          <ul expr:class='data:widget.sectionId in [&quot;footer-menu&quot;] ? &quot;link-list&quot; : &quot;link-list list-style&quot;'>
            <b:loop values='data:links' var='link'>
              <li><a expr:href='data:link.target'><data:link.name/></a></li>
            </b:loop>
          </ul>
        </b:tag>
      </b:if>
    </b:includable>
    <b:includable id='html-content'>
      <b:if cond='data:widget.sectionId == &quot;pbt-panel&quot;'>
        <b:if cond='data:content != &quot;&quot;'>
          <b:tag name='script' type='text/javascript'>
            <b:with expr:value='data:content' var='option'>
              <b:if cond='data:option.viewAllText'>var viewAllText = &quot;<data:option.viewAllText/>&quot;;</b:if>
              <b:if cond='data:option.dateFormat'>var dateFormat = &quot;<data:option.dateFormat/>&quot;;</b:if>
              <b:if cond='data:option.monthNames'>var monthNames = [&quot;<data:option.monthNames.jan/>&quot;,&quot;<data:option.monthNames.feb/>&quot;,&quot;<data:option.monthNames.mar/>&quot;,&quot;<data:option.monthNames.apr/>&quot;,&quot;<data:option.monthNames.may/>&quot;,&quot;<data:option.monthNames.jun/>&quot;,&quot;<data:option.monthNames.jul/>&quot;,&quot;<data:option.monthNames.aug/>&quot;,&quot;<data:option.monthNames.sep/>&quot;,&quot;<data:option.monthNames.oct/>&quot;,&quot;<data:option.monthNames.nov/>&quot;,&quot;<data:option.monthNames.dec/>&quot;];</b:if>
            </b:with>
          </b:tag>
        </b:if>
      <b:elseif cond='data:widget.sectionId == &quot;xdfcb-related-posts&quot;'/>
        <b:with value='data:title ? &quot;$title={&quot; + data:title + &quot;} &quot; : &quot;&quot;' var='relatedTitle'>
          <b:attr expr:value='data:relatedTitle + (data:content contains &quot;results&quot; ? data:content : &quot;&quot;)' name='data-shortcode'/>
        </b:with>
        <b:else/>
        <b:include name='widget-title'/>
        <div class='widget-content'>
          <b:if cond='data:title contains &quot;getMailchimp&quot;'>
            <b:attr expr:value='data:title' name='data-shortcode'/>
            <div class='mailchimp-header'>
              <h3 class='mailchimp-title'><data:messages.subscribe/></h3>
              <p class='mailchimp-text excerpt'><data:messages.getEmailNotifications/></p>
            </div>
            <form expr:action='data:content' expr:onsubmit='&quot;window.open(\&quot;&quot; + data:content + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' name='mc-embedded-subscribe-form' novalidate='' target='popupwindow'>
              <input class='mailchimp-email-address' expr:aria-label='data:messages.emailAddress' expr:placeholder='data:messages.emailAddress' name='EMAIL' type='email' value=''/>
              <input class='mailchimp-submit' expr:value='data:messages.subscribe' name='subscribe' type='submit'/>
            </form>
            <b:else/>
            <data:content/>
          </b:if>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='image-content'>
      <b:if cond='data:widget.sectionId == &quot;pbt-panel&quot;'>
        <b:tag name='script' type='text/javascript'>var noThumbnail = &quot;<b:eval expr='resizeImage(data:sourceUrl, 72, &quot;1:1&quot;)'/>&quot;;</b:tag>
        <b:elseif cond='data:widget.sectionId == &quot;main-logo&quot;'/>
        <a class='logo-img' expr:href='data:blog.homepageUrl.canonical' rel='home'>
          <img expr:alt='data:blog.title' expr:data-src='data:sourceUrl' expr:height='data:height' expr:src='data:sourceUrl' expr:title='data:blog.title' expr:width='data:width'>
            <b:loop values='[&quot;.png&quot;,&quot;.jpg&quot;,&quot;.gif&quot;]' var='imageType'>
              <b:attr cond='data:link and contains(data:link, data:imageType)' expr:value='data:link' name='data-dark-src'/>
            </b:loop>
          </img>
          <b:if cond='data:view.isMultipleItems'><h1 id='h1-off'><data:blog.title/></h1></b:if>
      	</a>
        <b:elseif cond='data:widget.sectionId == &quot;xdfcb-about-section&quot;'/>
        <a class='footer-logo custom-image' expr:href='data:blog.homepageUrl.canonical' rel='home'>
          <img expr:alt='data:blog.title' expr:data-src='data:sourceUrl' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'>
            <b:loop values='[&quot;.png&quot;,&quot;.jpg&quot;,&quot;.gif&quot;]' var='imageType'>
              <b:attr cond='data:link and contains(data:link, data:imageType)' expr:value='data:link' name='data-dark-src'/>
            </b:loop>
          </img>
        </a>
        <b:if cond='data:caption'>
          <div class='footer-info'>
            <b:if cond='data:title'><h3 class='title'><data:title/></h3></b:if>
            <b:if cond='data:caption'><p class='image-caption excerpt'><data:caption/></p></b:if>
          </div>
        </b:if>
        <b:else/>
        <div class='widget-content'>
          <div class='custom-image'>
            <b:tag cond='data:link' expr:href='data:link' name='a'>
              <img expr:alt='data:blog.title' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl'/>
            </b:tag>
          </div>
          <b:if cond='data:caption'>
            <p class='image-caption excerpt'><data:caption/></p>
          </b:if>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='text-content'>
      <b:include name='widget-title'/>
      <div class='widget-content excerpt'>
        <data:content/>
      </div>
    </b:includable>
    <b:includable id='popular-content'>
      <b:if cond='data:widget.sectionId == &quot;sidebar&quot;'>
        <div expr:class='data:i == 0 ? &quot;post cs item-&quot;+data:i : &quot;post item-&quot;+data:i'>
          <b:if cond='data:i == 0'>
            <a class='entry-inner' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'>
              <span class='entry-thumbnail mask'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/></span>
              <div class='entry-header entry-info'>
                <b:if cond='data:post.labels and (data:skin.vars.entrytag == &quot;1px&quot;)'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
                <h2 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h2>
                <b:if cond='data:widgets.Blog.first.allBylineItems.author or data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><b:if cond='data:widgets.Blog.first.allBylineItems.author'><span class='entry-author mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span></b:if><b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><span class='entry-time mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author and data:widgets.Blog.first.allBylineItems.timestamp.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></b:if></div></b:if>
              </div>
            </a>
            <b:else/>
            <span class='entry-index'><b:eval expr='data:i + 1'/></span>
            <div class='entry-header'>
              <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
              <b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><span class='entry-time'><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></div></b:if>
            </div>
          </b:if>
        </div>
        <b:else/>
        <div expr:class='&quot;post item-&quot;+data:i'>
          <a class='entry-thumbnail sz-4' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'>
            <b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/></a>
          <div class='entry-header'>
            <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
            <b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><span class='entry-time'><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></div></b:if>
          </div>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='featured-content'>
      <div class='post cs'>
        <a class='entry-inner' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'>
          <span class='entry-thumbnail mask'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/></span>
          <div class='entry-header entry-info'>
            <b:if cond='data:post.labels and (data:skin.vars.entrytag == &quot;1px&quot;)'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
            <h2 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h2>
            <b:if cond='data:widgets.Blog.first.allBylineItems.author or data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><b:if cond='data:widgets.Blog.first.allBylineItems.author'><span class='entry-author mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span></b:if><b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><span class='entry-time mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author and data:widgets.Blog.first.allBylineItems.timestamp.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></b:if></div></b:if>
          </div>
        </a>
      </div>
    </b:includable>
    <b:includable id='contact-form-content'>
      <div class='widget-content contact-form-widget'>
        <form class='contact-form-form' name='contact-form'>
          <input class='contact-form-name cf-s' expr:ariby='data:contactFormNameMsg' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' expr:placeholder='data:contactFormNameMsg' name='name' size='30' type='text' value=''/>
          <input class='contact-form-email cf-s' expr:ariby='data:contactFormEmailMsg + &quot; *&quot;' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' expr:placeholder='data:contactFormEmailMsg + &quot; *&quot;' name='email' size='30' type='text' value=''/>
          <textarea class='contact-form-email-message cf-s' cols='25' expr:ariby='data:contactFormMessageMsg + &quot; *&quot;' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' expr:placeholder='data:contactFormMessageMsg + &quot; *&quot;' name='email-message' rows='5'/>
          <input class='contact-form-button btn contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
          <p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
          <p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
        </form>
      </div>
    </b:includable>
    <b:includable id='theme-variables'>
      <b:tag name='script' type='text/javascript'>var pbt={fixedMenu:<b:eval expr='data:skin.vars.fixedmenu == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,fixedSidebar:<b:eval expr='data:skin.vars.fixedsidebar == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,entryTag:<b:eval expr='data:skin.vars.entrytag == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,noTitle:&quot;<data:messages.noTitle/>&quot;,viewAll:&quot;<data:messages.viewAll/>&quot;,noResults:&quot;<data:messages.noResultsFound/>&quot;,postAuthor:<b:eval expr='data:widgets.Blog.first.allBylineItems.author ? &quot;true&quot; : &quot;false&quot;'/>,postAuthorLabel:&quot;<b:eval expr='data:widgets.Blog.first.allBylineItems.author.label ? data:widgets.Blog.first.allBylineItems.author.label : &quot;&quot;'/>&quot;,postDate:<b:eval expr='data:widgets.Blog.first.allBylineItems.timestamp ? &quot;true&quot; : &quot;false&quot;'/>,postDateLabel:&quot;<b:eval expr='data:widgets.Blog.first.allBylineItems.timestamp.label ? data:widgets.Blog.first.allBylineItems.timestamp.label : &quot;&quot;'/>&quot;}</b:tag>
    </b:includable>
    <b:includable id='pbt-share-modal'>
      <div class='share-modal'>
        <div class='modal-header'>
          <span class='title'><data:messages.shareToOtherApps/></span>
          <button class='hide-modal' expr:aria-label='data:messages.showLess'/>
        </div>
        <b:with value='data:view.url.canonical' var='shareUrl'>
          <b:with value='data:view.title.jsEscaped' var='shareTitle'>
            <ul class='share-b social color'>
              <li class='facebook'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:shareUrl' href='#' rel='nofollow noopener' title='Facebook'/></li>
              <li class='twitter'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:shareUrl + &quot;&amp;text=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='Twitter'/></li>
              <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:shareTitle + &quot; | &quot; + data:shareUrl' href='#' rel='nofollow noopener' title='WhatsApp'/></li>
              <li class='pinterest-p'><a class='fa-pinterest-p btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:shareUrl + &quot;&amp;media=&quot; + data:view.featuredImage + &quot;&amp;description=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='Pinterest'/></li>
              <li class='linkedin'><a class='fa-linkedin-in btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.linkedin.com/shareArticle?mini=true&amp;url=&quot; + data:shareUrl + &quot;&amp;title=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='LinkedIn'/></li>
              <li class='reddit'><a class='fa-reddit-alien btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://reddit.com/submit?url=&quot; + data:shareUrl + &quot;&amp;title=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='Reddit'/></li>
              <li class='vk'><a class='fa-vk btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://vk.com/share.php?url=&quot; + data:shareUrl' href='#' rel='nofollow noopener' title='VKontakte'/></li>
              <li class='tumblr'><a class='fa-tumblr btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.tumblr.com/share/link?url=&quot; + data:shareUrl + &quot;&amp;name=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='Tumblr'/></li>
              <li class='telegram'><a class='fa-telegram-plane btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://telegram.me/share/url?url=&quot; + data:shareUrl + &quot;&amp;text=&quot; + data:shareTitle' href='#' rel='nofollow noopener' title='Telegram'/></li>
              <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:shareTitle + &quot;&amp;body=&quot; + data:shareUrl' href='#' rel='nofollow noopener' title='Email'/></li>
            </ul>
          </b:with>
          <div class='modal-footer'>
            <span class='title'><data:messages.copy/> <data:messages.postLink/></span>
            <div class='copy-link'>
              <input expr:value='data:shareUrl' readonly='readonly'/>
              <button expr:aria-label='data:messages.copy'><data:messages.copy/></button>
            </div>
          </div>
        </b:with>
      </div>
      <b:tag class='overlay' id='share-overlay' name='div'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Header'>
    <b:includable id='main' var='this'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
    </b:includable>
    <b:includable id='image'>
      <a class='logo-img' expr:href='data:blog.homepageUrl.canonical'>
        <img expr:alt='data:blog.title.escaped' expr:height='data:height' expr:src='data:image' expr:title='data:blog.title.escaped' expr:width='data:width'/>
        <b:if cond='data:view.isMultipleItems'><b:if cond='data:widget.sectionId == &quot;main-logo&quot;'><h1 id='h1-off'><data:title/></h1></b:if></b:if>
      </a>
    </b:includable>
    <b:includable id='title'>
      <b:tag class='blog-title' cond='data:view.isMultipleItems' name='h1'>
        <b:tag class='blog-title' cond='!data:view.isMultipleItems' name='span'>
          <b:tag expr:href='data:blog.homepageUrl.canonical' name='a'>
            <data:title/>
          </b:tag>
        </b:tag>
      </b:tag>
    </b:includable>
    <b:includable id='behindImageStyle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='description'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='LinkList'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='TextList'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <ul class='text-list list-style'>
          <b:loop values='data:items' var='item'>
            <li><data:item/></li>
          </b:loop>
        </ul>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='HTML'>
    <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Text'>
    <b:includable id='main'>
      <b:include name='text-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Blog'>
    <b:includable id='main' var='this'>
      <b:class cond='data:view.isMultipleItems' name='index-blog flex-col'/>
      <b:include cond='data:view.isHomepage' name='blogPostsTitle'/>
      <b:include name='searchMessage'/>
      <b:if cond='!data:posts.empty'>
        <div class='blog-posts'>
          <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;index-post-wrap grid-items&quot; : &quot;index-post-wrap list-items&quot;'/>
          <b:class cond='data:view.isSingleItem' name='item-post-wrap flex-col'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='postCommentsAndAd'/>
          </b:loop>
        </div>
        <b:include cond='data:view.isMultipleItems' name='ajaxPagination'/>
      </b:if>
      <b:include name='feedLinks'/>
    </b:includable>
    <b:includable id='blogPostsTitle'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;{hide}&quot;'>
        <div class='title-wrap blog1-title'><h3 class='title'><data:blog.jumpLinkMessage/></h3></div>
      </b:if>
    </b:includable>
    <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='addComments'>
      <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'><data:messages.postAComment/></a>
    </b:includable>
    <b:includable id='ajaxPagination'>
      <!-- Ajax Pagination on Index -->
      <div class='blog-pager' id='blog-pager'>
        <b:if cond='data:olderPageUrl'>
          <a class='blog-pager-older-link load-more btn' expr:data-load='data:olderPageUrl.canonical' href='#' id='xdfcb-load-more-link'><b:include data='{ message: &quot;loadMorePosts&quot; }' name='theme-custom-lang'/></a>
          <span class='loading'><div class='loader'/></span>
          <span class='no-more load-more btn'><data:messages.noResultsFound/></span>
          <b:else/>
          <span class='no-more load-more btn show'><data:messages.noResultsFound/></span>
        </b:if>
      </div>
    </b:includable>
    <b:includable id='backLinks' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentDeleteIcon' var='comment'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentForm' var='post'>
      <div class='comment-form'>
        <a name='comment-form'/>
        <b:include data='post' name='commentFormIframeSrc'/>
        <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='90px' id='comment-editor' name='comment-editor' src='' width='100%'/>
        <data:post.cmtfpIframe/>
        <script type='text/javascript'>
          BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
        </script>
      </div>
    </b:includable>
    <b:includable id='commentFormIframeSrc' var='post'>
      <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=soho&quot;' id='comment-editor-src' rel='nofollow noopener' title='Comment Form Link'/>
    </b:includable>
    <b:includable id='commentItem' var='comment'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentList' var='comments'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentPicker' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='comments' var='post'>
      <a name='comments'/>
      <section class='comments threaded flex-col' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
        <b:class expr:name='data:post.numberOfComments != 0 ? &quot;has-comments&quot; : &quot;no-comments&quot;'/>
        <b:include name='commentsTitle'/>
        <b:if cond='data:post.allowNewComments'>
          <b:if cond='data:this.messages.blogComment'><p class='comments-message excerpt'><data:this.messages.blogComment/></p></b:if>
          <b:else/>
          <b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments == 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if>
        </b:if>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.numberOfComments != 0'>
            <div class='comments-content'>
              <div id='comment-holder'>
                <data:post.commentHtml/>
              </div>
            </div>
          </b:if>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          </b:if>
          <b:if cond='!data:post.allowNewComments'><b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments != 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if></b:if>
          <b:else/>
          <p class='comments-message excerpt'>Please Select Embedded Mode To Show The Comment System.<em>*</em></p>
        </b:if>
      </section>
    </b:includable>
    <b:includable id='commentsTitle'>
      <!-- Comments Title -->
      <div class='title-wrap comments-title'><b:class expr:name='data:this.messages.blogComment ? &quot;has-message&quot; : &quot;no-message&quot;'/><h3 class='title'><b:if cond='data:post.numberOfComments != 0'><b:if cond='data:allBylineItems.comments.label contains &quot;disqus&quot; or data:allBylineItems.comments.label contains &quot;facebook&quot;'><data:messages.postAComment/><b:else/><data:post.numberOfComments/> <data:messages.comments/></b:if><b:else/><data:messages.postAComment/></b:if></h3></div>
    </b:includable>
    <b:includable id='defaultAdUnit'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline' var='post'>
      <!-- Post Entry Meta -->
      <b:if cond='data:view.isMultipleItems'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp'>
          <div class='entry-meta'>
            <b:class cond='data:skin.vars.gridstyle == &quot;1px&quot; and (data:skin.vars.summary == &quot;1px&quot;)' name='has-snip'/>
            <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
            <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
          </div>
        </b:if>
      </b:if>
      <b:if cond='data:view.isPost'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp or data:allBylineItems.share'>
          <b:class name='has-meta'/>
          <div class='entry-meta'>
            <div class='align-left'>
              <b:class cond='data:allBylineItems.timestamp' name='has-time'/>
              <b:if cond='data:allBylineItems.author'><span class='entry-avatar'><span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/></span></b:if>
              <b:tag class='al-items' cond='data:allBylineItems.author and data:allBylineItems.timestamp' name='div'>
              <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
              <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
              </b:tag>
            </div>
            <b:if cond='data:allBylineItems.share'>
              <div class='align-right'>
                <button class='share-toggle btn' expr:aria-label='data:messages.share'/>
              </div>
            </b:if>
          </div>
        </b:if>
      </b:if>
    </b:includable>
    <b:includable id='homePageLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='indexPost' var='post'>
      <!-- Index Post Content -->
      <b:include data='post' name='postFeaturedImage'/>
      <div class='entry-header'>
        <b:include data='post' name='postHeader'/>
        <b:include cond='data:skin.vars.summary == &quot;1px&quot;' data='post' name='postBodySnippet'/>
        <b:include data='post' name='headerByline'/>
      </div>
    </b:includable>
    <b:includable id='inlineAd' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='itemPost' var='post'>
      <!-- Item Post Content -->
      <b:include data='post' name='postMeta'/>
      <div class='item-post-inner flex-col'>
        <div class='entry-header p-eh'>
          <b:include data='post' name='postHeader'/>
        </div>
        <div class='entry-content-wrap flex-col'>
          <b:include data='post' name='postBody'/>
          <b:include cond='data:view.isPost and data:allBylineItems.labels' data='post' name='postLabels'/>
        </div>
        <b:include cond='data:view.isPost and data:allBylineItems.share' data='post' name='postShareButtons'/>
      </div>
      <b:include cond='data:view.isPost' data='post' name='postFooter'/>
    </b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='nextPageLink'>
      <b:if cond='data:olderPageUrl'>
        <a class='post-nav-link post-nav-older-link' expr:href='data:olderPageUrl.canonical'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-older-link'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='post' var='post'>
      <!-- Index Posts -->
      <b:if cond='data:view.isMultipleItems'>
        <b:include data='post' name='indexPost'/>
      </b:if>
      <!-- Item Post -->
      <b:if cond='data:view.isSingleItem'>
        <b:include data='post' name='itemPost'/>
      </b:if>
    </b:includable>
    <b:includable id='postAuthor' var='post'>
      <!-- Post Author -->
      <span class='entry-author mi'><b:if cond='data:allBylineItems.author.label'><span class='by sp'><data:allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span>
    </b:includable>
    <b:includable id='postBody' var='post'> 
      <!-- Ads before post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;xdfcb-main-before-ad&quot;' id='before-ad' name='div'/></b:if>
      <!-- Post Body Entry Content-->
      <div class='post-body entry-content' id='post-body'>
        <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
<!-- body -->
<ins class='adsbygoogle' data-ad-client='ca-pub-4502383117355497' data-ad-slot='2466237464' style='display:inline-block;width:728px;height:90px'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
        <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
<!-- body -->
<ins class='adsbygoogle' data-ad-client='ca-pub-4502383117355497' data-ad-slot='2466237464' style='display:inline-block;width:728px;height:90px'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
        <data:post.body/>
        <script async='async' crossorigin='anonymous' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4502383117355497'/>
<!-- header ads -->
<ins class='adsbygoogle' data-ad-client='ca-pub-4502383117355497' data-ad-format='auto' data-ad-slot='7381552608' data-full-width-responsive='true' style='display:block'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
      </div>
      <!-- Ads after post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;xdfcb-main-after-ad&quot;' id='after-ad' name='div'/></b:if>
    </b:includable>
    <b:includable id='postBodySnippet' var='post'><p class='entry-excerpt excerpt'><b:eval expr='data:post.snippets.long snippet { length: 101 }'/></p></b:includable>
    <b:includable id='postBreadcrumbs' var='post'>
      <!-- Post Breadcrumbs -->
      <b:if cond='data:view.isPost'>
        <b:if cond='data:skin.vars.breadcrumb == &quot;1px&quot;'><nav id='breadcrumb'><a class='home' expr:href='data:blog.homepageUrl'><data:messages.home/></a><b:if cond='data:post.labels'><em class='separator'/><a class='label' expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></b:if></nav></b:if>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.name.jsonEscaped/><b:else/><data:messages.posts/></b:if>&quot;,&quot;item&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.url.canonical.jsonEscaped/><b:else/><b:eval expr='data:blog.homepageUrl.canonical.jsonEscaped + &quot;search/&quot;'/></b:if>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:3,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
      <b:if cond='data:view.isPage'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
    </b:includable>
    <b:includable id='postCategory' var='post'>
      <!-- Post Label -->
      <b:if cond='data:post.labels'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
    </b:includable>
    <b:includable id='postCommentsAndAd' var='post'>
      <article>
        <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;post hentry item-&quot; + data:i : &quot;post hentry item-&quot; + data:i'/>
        <b:class cond='data:view.isSingleItem' name='item-post hentry flex-col'/>
        <b:include data='post' name='post'/>
      </article>
      <b:if cond='data:view.isSingleItem and data:post.allowComments'>
        <!-- Post Comments -->
        <div class='xdfcb-blog-post-comments p-widget' expr:data-shortcode='data:allBylineItems.comments.label contains &quot;type&quot; ? data:allBylineItems.comments.label : &quot;$type={blogger}&quot;'>
          <b:include data='post' name='threadedCommentsDisqus'/>
          <b:include data='post' name='comments'/>
        </div>
      </b:if>
      <!-- Post Navigation -->
      <b:include cond='data:skin.vars.postnav == &quot;1px&quot;' name='postPagination'/>
    </b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postFeaturedImage' var='post'>
      <!-- Post Featured Image -->
      <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/></a>
    </b:includable>
    <b:includable id='postFooter' var='post'>
      <!-- Post Footer Items -->
      <b:tag class='post-footer flex-col' cond='data:post.author.aboutMe or (data:widgets.HTML any w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;)' name='footer'>
        <b:include cond='data:post.author.aboutMe' data='post' name='postFooterAuthorProfile'/>
        <b:include cond='data:widgets.HTML any w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;' data='post' name='relatedPosts'/>
      </b:tag>
    </b:includable>
    <b:includable id='postFooterAuthorProfile' var='post'>
      <div class='about-author p-widget'>
        <div class='author-avatar entry-avatar'>
          <span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/>
        </div>
        <div class='author-description flex-col'>
          <h3 class='author-title'><b:tag cond='data:post.author.profileUrl' expr:alt='data:post.author.name' expr:href='data:post.author.profileUrl' name='a' rel='nofollow noopener' target='_blank'><data:post.author.name/></b:tag></h3>
          <p class='author-text excerpt'><data:post.author.aboutMe/></p>
        </div>
      </div>
    </b:includable>
    <b:includable id='postHeader' var='post'>
      <b:include cond='data:view.isSingleItem' data='post' name='postBreadcrumbs'/>
      <b:include data='post' name='postTitle'/>
      <b:include cond='data:view.isPost' data='post' name='headerByline'/>
    </b:includable>
    <b:includable id='postJumpLink' var='post'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
        <a class='read-more' expr:href='data:post.url.canonical'><data:blog.jumpLinkMessage/></a>
      </b:if>
    </b:includable>
    <b:includable id='postLabels' var='post'>
      <b:if cond='data:post.labels'>
        <div class='entry-labels'>
          <b:if cond='data:allBylineItems.labels.label'><span class='labels-label btn'><data:allBylineItems.labels.label/></span></b:if>
          <b:loop values='data:post.labels' var='label'>
            <a class='label-link btn' expr:href='data:label.url' rel='tag'><data:label.name/></a>
          </b:loop>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postMeta' var='post'>
      <b:if cond='data:view.isPost'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;NewsArticle&quot;,&quot;mainEntityOfPage&quot;:{&quot;@type&quot;:&quot;WebPage&quot;,&quot;@id&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;},&quot;headline&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;description&quot;:&quot;<data:post.snippets.short.jsonEscaped/>&quot;,&quot;datePublished&quot;:&quot;<data:post.date.iso8601.jsonEscaped/>&quot;,&quot;dateModified&quot;:&quot;<data:post.lastUpdated.iso8601.jsonEscaped/>&quot;,&quot;image&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,<b:if cond='data:post.featuredImage.isResizable'>&quot;url&quot;:&quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:675&quot;)'/>&quot;,&quot;height&quot;:675,&quot;width&quot;:1200<b:else/>&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,&quot;height&quot;:348,&quot;width&quot;:1200</b:if>},&quot;author&quot;:{&quot;@type&quot;:&quot;Person&quot;,&quot;name&quot;:&quot;<data:post.author.name.jsonEscaped/>&quot;},&quot;publisher&quot;:{&quot;@type&quot;:&quot;Organization&quot;,&quot;name&quot;:&quot;Blogger&quot;,&quot;logo&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,&quot;width&quot;:206,&quot;height&quot;:60}}}</script>
      </b:if>
    </b:includable>
    <b:includable id='postMetadataJSONImage'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postMetadataJSONPublisher'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postPagination'>
      <b:if cond='data:view.isPost'>
        <div class='post-nav p-widget'>
          <b:include name='previousPageLink'/>
          <b:include name='nextPageLink'/>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons' var='post'>
      <!-- Post Share Buttons & Modal -->
      <div class='post-share'>
        <ul class='share-a social color'>
          <li class='share-label'><span class='sl-btn btn'><i class='sl-ico'/></span></li>
          <li class='facebook has-span'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='Facebook'><span>Facebook</span></a></li>
          <li class='twitter has-span'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='nofollow noopener' title='Twitter'><span>Twitter</span></a></li>
          <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='WhatsApp'/></li>
          <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='Email'/></li>
          <li class='show-more'><button class='btn' expr:aria-label='data:messages.showMore'/></li>
        </ul>
      </div>
    </b:includable>
    <b:includable id='postTimestamp' var='post'>
      <!-- Post Timestamp -->
      <span class='entry-time mi'><b:if cond='data:allBylineItems.author and data:allBylineItems.timestamp.label'><span class='sp'><data:allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span>
    </b:includable>
    <b:includable id='postTitle' var='post'>
      <!-- Post Title Index and Item -->
      <b:if cond='data:view.isMultipleItems'>
        <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle' rel='bookmark'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
      </b:if>
      <b:if cond='data:view.isSingleItem'>
        <h1 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h1>
      </b:if>
    </b:includable>
    <b:includable id='previousPageLink'>
      <b:if cond='data:newerPageUrl'>
        <a class='post-nav-link post-nav-newer-link' expr:href='data:newerPageUrl.canonical'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-newer-link'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
    <b:includable id='relatedPosts' var='post'>
      <!-- Related Posts -->
      <div class='p-widget' id='related-wrap'>
        <div class='title-wrap related-title'>
          <b:with value='data:widgets.HTML filter (w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;) map (w =&gt; w.title)' var='pbtTitle'>
            <h3 class='title'><b:eval expr='data:pbtTitle.first ? data:pbtTitle.first : data:messages.youMayLikeThesePosts'/></h3>
          </b:with>
          <a class='title-link' expr:href='data:post.labels ? data:post.labels.first.url : &quot;/search&quot;'><data:messages.viewAll/></a>
        </div>
        <div class='related-content'>
          <b:if cond='data:post.labels'>
            <div class='related-tag' expr:data-id='data:post.id' expr:data-label='data:post.labels.first.name'/>
            <b:else/>
            <div class='related-tag' data-label='recent' expr:data-id='data:post.id'/>
          </b:if>
        </div> 
      </div>  
    </b:includable>
    <b:includable id='searchMessage'>
      <!-- Search Message -->
      <b:if cond='data:posts.empty'>
        <b:class name='no-posts'/>
      </b:if>
      <b:if cond='data:view.search.query'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'>&quot;<data:view.search.query/>&quot;</span>
            <b:else/>
            <span class='query-info query-success'>&quot;<data:view.search.query/>&quot;</span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.search.label'>
        <div class='queryMessage '>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-label query-error'><data:view.search.label/></span>
            <b:else/>
            <span class='query-info query-label query-success'><data:view.search.label/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isArchive'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'><data:view.archive.rangeMessage/></span>
            <b:else/>
            <span class='query-info query-success'><data:view.archive.rangeMessage/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isError'>
        <div class='errorWrap'>
          <h3>404</h3>
          <h4><data:messages.theresNothingHere/></h4>
          <p><data:navMessage/></p>
          <a class='homepage btn' expr:href='data:blog.homepageUrl'><data:messages.home/></a>
        </div>
      </b:if>
      <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
    </b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentJs' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedComments' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentsDisqus' var='post'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PopularPosts'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:class expr:name='data:widget.sectionId == &quot;sidebar&quot; ? &quot;popular-items&quot; : &quot;default-items&quot;'/>
        <b:loop index='i' values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FeaturedPost'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='content' var='post'>
      <b:include name='featured-content'/>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='ContactForm'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='contact-form-content'/>
    </b:includable>       
  </b:defaultmarkup>
  <b:defaultmarkup type='Label'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
    <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
    <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FollowByEmail'>
    <b:includable id='main' var='this'>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
		<p>This gadget is no longer available.</p>
      </div>
    </b:includable>
  </b:defaultmarkup> 
  <b:defaultmarkup type='Image'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
  </b:defaultmarkup> 
  <b:defaultmarkup type='BlogArchive'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class name='archive-list'/>
        <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;, &quot;HIERARCHY&quot;}' name='flat'/>
      </div>
    </b:includable>
    <b:includable id='flat'>
      <ul class='list-style'>
        <b:loop values='data:data' var='i'>
          <li><a class='archive-name' expr:href='data:i.url'><data:i.name/><b:if cond='data:i.post-count'><b:class name='has-count'/><span class='archive-count count-style'>(<data:i.post-count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PageList'>
    <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='pagelist-content'/>
    </b:includable>
    <b:includable id='overflowButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='overflowablePageList'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='pageLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='pageList'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogSearch'>
    <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='searchForm'/>
    </b:includable>
    <b:includable id='searchForm'>
      <form class='search-form' expr:action='data:blog.searchUrl'>
        <b:attr cond='!data:view.isPreview' name='target' value='_top'/>
        <b:include name='urlParamsAsFormInput'/>
        <input autocomplete='off' class='search-input' expr:aria-label='data:messages.search' expr:placeholder='data:messages.search' name='q' type='search' value=''/>
        <b:include name='searchSubmit'/>
      </form>
    </b:includable>
    <b:includable id='searchSubmit'>
      <input class='search-action btn' expr:value='data:messages.ok' type='submit'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Profile'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='authorProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' expr:src='resizeImage(data:authorPhoto.image, 50, &quot;1:1&quot;)'/>
    </b:includable>
    <b:includable id='defaultProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' src='https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/w50-h50-p-k-no-nu/avatar.jpg'/>
    </b:includable>
    <b:includable id='userProfileInfo' var='this'>
      <div class='profile-info'>
        <dl class='profile-datablock'>
          <b:include name='userProfileData'/>
        </dl>
        <b:include name='viewProfileLink'/>
      </div>
    </b:includable>
    <b:includable id='teamProfileLink' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:display-name/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
    <b:includable id='userProfile' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:displayname/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
  </b:defaultmarkup>
  </b:defaultmarkups>
  
  </head>
<body>
  
  
  
  
  <amp-auto-ads data-ad-client='ca-pub-4502383117355497' type='adsense'>
</amp-auto-ads>
<b:include name='theme-body-class'/>
<b:if cond='data:view.isLayoutMode or (data:widgets any w =&gt; w.sectionId == &quot;pbt-panel&quot;)'>
  <!-- Theme Options -->
  <div id='theme-options' style='display:none'>
    <b:section class='pbt-panel' id='pbt-panel' maxwidgets='2' name='Theme Options' showaddelement='no'>
      <b:widget id='Image52' locked='true' title='Default Thumbnail' type='Image' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='displayUrl'>https://1.bp.blogspot.com/-rI4UCIrwEI4/YN3nGkf0nCI/AAAAAAAAAD0/DQ6fW7eCps8NL7S0oh374KFg1MsWUf2GQCLcBGAsYHQ/s72-c/ptb-nth.png</b:widget-setting>
          <b:widget-setting name='displayHeight'>72</b:widget-setting>
          <b:widget-setting name='sectionWidth'>150</b:widget-setting>
          <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
          <b:widget-setting name='displayWidth'>72</b:widget-setting>
          <b:widget-setting name='link'/>
          <b:widget-setting name='caption'/>
        </b:widget-settings>
        <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
        <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
      </b:widget>
      <b:widget id='HTML50' locked='true' title='JSON Variables' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
      </b:widget>
    </b:section>
  </div>
</b:if>
<!-- Site Content -->
<div id='outer-wrapper'>
  <header id='header-wrapper'>
    <div class='main-header'>
      <div class='header-inner'>
        <div class='header-header flex-c'>
          <div class='container row-x1'>
            <div class='header-items'>
              <div class='flex-left'>
                <b:tag aria-label='Show Menu' class='mobile-menu-toggle' name='button'/>
                <b:if cond='data:view.isLayoutMode or (data:widgets.Image any w =&gt; w.sectionId == &quot;main-logo&quot;)'>
                  <b:section class='main-logo' id='main-logo' maxwidgets='1' name='Header Logo' showaddelement='no'>
                    <b:widget id='Image50' locked='true' title='' type='Image' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEjnHn22vJL9GZes9HtQtmQX-X4il9d_Lp5q0jLrGLykcG_bcDVg528va58JcBWxejNFWxOJzaj-ms1oxGHIICWe2YddVkc2RSHpLL_mjr0rW-YAJQyf0ONkUcEIxUQ_1EBd5ZtZop4dMUmFojueLHqPzp-VDW7jQCrxOxG6UOhI2Ku3Fh1wh3V6mkxsMg=s150</b:widget-setting>
                        <b:widget-setting name='displayHeight'>84</b:widget-setting>
                        <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                        <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
                        <b:widget-setting name='displayWidth'>150</b:widget-setting>
                        <b:widget-setting name='link'/>
                        <b:widget-setting name='caption'/>
                      </b:widget-settings>
                      <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                      <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
                    </b:widget>
                  </b:section>
                <b:else/>
                  <div class='main-logo'>
                    <b:tag class='title' expr:name='data:view.isMultipleItems ? &quot;h1&quot; : &quot;span&quot;'>
                      <a class='homepage' expr:href='data:blog.homepageUrl.canonical' rel='home'><data:blog.title/></a>
                    </b:tag>
                  </div>
                </b:if>
                <b:section class='xdfcb-main-menu' id='xdfcb-main-menu' maxwidgets='1' name='Header Menu' showaddelement='no'>
                  <b:widget id='LinkList200' locked='true' title='' type='LinkList' visible='true'>
                    <b:widget-settings>
                      <b:widget-setting name='link-3'>https://www.blogger.com/profile/03850443723801465813</b:widget-setting>
                      <b:widget-setting name='sorting'>NONE</b:widget-setting>
                      <b:widget-setting name='text-1'>Features</b:widget-setting>
                      <b:widget-setting name='link-1'>https://ourancientearth.blogspot.com/#</b:widget-setting>
                      <b:widget-setting name='text-0'>Home</b:widget-setting>
                      <b:widget-setting name='link-2'>https://ourancientearth.blogspot.com/2023/01/instagram-growth-hack.html</b:widget-setting>
                      <b:widget-setting name='text-3'>Blogger</b:widget-setting>
                      <b:widget-setting name='link-0'>https://ourancientearth.blogspot.com/</b:widget-setting>
                      <b:widget-setting name='text-2'>_Featured Posts</b:widget-setting>
                    </b:widget-settings>
                    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                    <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
                  </b:widget>
                </b:section>
              </div>
              <div class='flex-right'>
                <div class='toggle-wrap'>
                  <b:tag class='search-toggle show-search btn' expr:aria-label='data:messages.search' name='button'/>
                </div>
              </div>
              <div class='main-search'>
                <form class='search-form' expr:action='data:blog.searchUrl'>
                  <b:attr cond='!data:view.isPreview' name='target' value='_top'/>
                  <input autocomplete='off' class='search-input' expr:aria-label='data:messages.search' expr:placeholder='data:messages.search' name='q' type='search' value=''/>
                  <button class='search-toggle search-close btn' type='reset'/>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <b:if cond='data:view.isLayoutMode or (data:widgets any w =&gt; w.sectionId == &quot;headerbar&quot;)'>
      <nav class='headerbar-wrap flex-c'>
        <div class='container row-x1'>
          <div class='headerbar-items flex-sb'>
            <b:section class='headerbar' id='headerbar' maxwidgets='2' name='Header Bar' showaddelement='no'>
              <b:widget id='LinkList201' locked='true' title='' type='LinkList' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='sorting'>NONE</b:widget-setting>
                  <b:widget-setting name='text-1'>puzzle</b:widget-setting>
                  <b:widget-setting name='link-1'>https://ourancientearth.blogspot.com/p/puzzle.html</b:widget-setting>
                  <b:widget-setting name='text-0'>Trending</b:widget-setting>
                  <b:widget-setting name='link-2'>https://ourancientearth.blogspot.com/p/3-best-video-editor2023.html</b:widget-setting>
                  <b:widget-setting name='link-0'>/search/label/trending</b:widget-setting>
                  <b:widget-setting name='text-2'>video editors</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
              </b:widget>
              <b:widget id='LinkList202' locked='true' title='Follow Us' type='LinkList' visible='true'>
                <b:widget-settings>
                  <b:widget-setting name='link-3'>https://github.com/Ajay-Sahani</b:widget-setting>
                  <b:widget-setting name='sorting'>NONE</b:widget-setting>
                  <b:widget-setting name='text-1'>youtube</b:widget-setting>
                  <b:widget-setting name='link-1'>https://youtube.com/@RAJOOKUMARNISHAD</b:widget-setting>
                  <b:widget-setting name='text-0'>{getSocial}</b:widget-setting>
                  <b:widget-setting name='link-2'>https://instagram.com/ajay._.sahani?igshid=YmMyMTA2M2Y=</b:widget-setting>
                  <b:widget-setting name='text-3'>git hub</b:widget-setting>
                  <b:widget-setting name='link-0'>#</b:widget-setting>
                  <b:widget-setting name='text-2'>instagram</b:widget-setting>
                </b:widget-settings>
                <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
              </b:widget>
            </b:section>
            <b:if cond='data:widgets.LinkList filter (w =&gt; w.id == &quot;LinkList202&quot;) any (w =&gt; w.sectionId == &quot;headerbar&quot;)'>
              <b:with value='data:widgets.LinkList filter (w =&gt; w.id == &quot;LinkList202&quot;) map (w =&gt; w.title)' var='pbtTitle'>
                <button class='social-toggle' expr:aria-label='data:pbtTitle.first ? data:pbtTitle.first : &quot;Follow Us&quot;'><b:tag class='title' cond='data:pbtTitle.first' name='span'><b:eval expr='data:pbtTitle.first ? data:pbtTitle.first : &quot;&quot;'/></b:tag><b:class cond='!data:pbtTitle.first' name='no-title'/></button>
              </b:with>
            </b:if>
          </div>
        </div>
      </nav>
    </b:if>
  </header>
  <div class='flex-c' id='content-wrapper'>
    <div class='container row-x1 flex-sb'>
      <main id='main-wrapper'>
        <b:section class='main' id='main' maxwidgets='1' name='Main Posts' showaddelement='yes'>
          <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='commentLabel'>$type={blogger}</b:widget-setting>
              <b:widget-setting name='showShareButtons'>true</b:widget-setting>
              <b:widget-setting name='authorLabel'>by</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='timestampLabel'>&#8226;</b:widget-setting>
              <b:widget-setting name='reactionsLabel'/>
              <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLocation'>true</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showDateHeader'>false</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='postLocationLabel'>Location:india</b:widget-setting>
              <b:widget-setting name='showAuthor'>true</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showLabels'>true</b:widget-setting>
              <b:widget-setting name='postLabelsLabel'>Tags</b:widget-setting>
              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
              <b:widget-setting name='showInlineAds'>true</b:widget-setting>
              <b:widget-setting name='showReactions'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:class cond='data:view.isMultipleItems' name='index-blog flex-col'/>
      <b:include cond='data:view.isHomepage' name='blogPostsTitle'/>
      <b:include name='searchMessage'/>
      <b:if cond='!data:posts.empty'>
        <div class='blog-posts'>
          <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;index-post-wrap grid-items&quot; : &quot;index-post-wrap list-items&quot;'/>
          <b:class cond='data:view.isSingleItem' name='item-post-wrap flex-col'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='postCommentsAndAd'/>
          </b:loop>
        </div>
        <b:include cond='data:view.isMultipleItems' name='ajaxPagination'/>
      </b:if>
      <b:include name='feedLinks'/>
    </b:includable>
            <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='addComments'>
      <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'><data:messages.postAComment/></a>
    </b:includable>
            <b:includable id='ajaxPagination'>
      <!-- Ajax Pagination on Index -->
      <div class='blog-pager' id='blog-pager'>
        <b:if cond='data:olderPageUrl'>
          <a class='blog-pager-older-link load-more btn' expr:data-load='data:olderPageUrl.canonical' href='#' id='xdfcb-load-more-link'><b:include data='{ message: &quot;loadMorePosts&quot; }' name='theme-custom-lang'/></a>
          <span class='loading'><div class='loader'/></span>
          <span class='no-more load-more btn'><data:messages.noResultsFound/></span>
          <b:else/>
          <span class='no-more load-more btn show'><data:messages.noResultsFound/></span>
        </b:if>
      </div>
    </b:includable>
            <b:includable id='backLinks' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='blogPostsTitle'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;{hide}&quot;'>
        <div class='title-wrap blog1-title'><h3 class='title'><data:blog.jumpLinkMessage/></h3></div>
      </b:if>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentDeleteIcon' var='comment'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentForm' var='post'>
      <div class='comment-form'>
        <a name='comment-form'/>
        <b:include data='post' name='commentFormIframeSrc'/>
        <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='90px' id='comment-editor' name='comment-editor' src='' width='100%'/>
        <data:post.cmtfpIframe/>
        <script type='text/javascript'>
          BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
        </script>
      </div>
    </b:includable>
            <b:includable id='commentFormIframeSrc' var='post'>
      <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=soho&quot;' id='comment-editor-src' rel='nofollow noopener' title='Comment Form Link'/>
    </b:includable>
            <b:includable id='commentItem' var='comment'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentList' var='comments'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentPicker' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='comments' var='post'>
      <a name='comments'/>
      <section class='comments threaded flex-col' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
        <b:class expr:name='data:post.numberOfComments != 0 ? &quot;has-comments&quot; : &quot;no-comments&quot;'/>
        <b:include name='commentsTitle'/>
        <b:if cond='data:post.allowNewComments'>
          <b:if cond='data:this.messages.blogComment'><p class='comments-message excerpt'><data:this.messages.blogComment/></p></b:if>
          <b:else/>
          <b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments == 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if>
        </b:if>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.numberOfComments != 0'>
            <div class='comments-content'>
              <div id='comment-holder'>
                <data:post.commentHtml/>
              </div>
            </div>
          </b:if>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          </b:if>
          <b:if cond='!data:post.allowNewComments'><b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments != 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if></b:if>
          <b:else/>
          <p class='comments-message excerpt'>Please Select Embedded Mode To Show The Comment System.<em>*</em></p>
        </b:if>
      </section>
    </b:includable>
            <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
            <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
            <b:includable id='commentsTitle'>
      <!-- Comments Title -->
      <div class='title-wrap comments-title'><b:class expr:name='data:this.messages.blogComment ? &quot;has-message&quot; : &quot;no-message&quot;'/><h3 class='title'><b:if cond='data:post.numberOfComments != 0'><b:if cond='data:allBylineItems.comments.label contains &quot;disqus&quot; or data:allBylineItems.comments.label contains &quot;facebook&quot;'><data:messages.postAComment/><b:else/><data:post.numberOfComments/> <data:messages.comments/></b:if><b:else/><data:messages.postAComment/></b:if></h3></div>
    </b:includable>
            <b:includable id='defaultAdUnit'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline' var='post'>
      <!-- Post Entry Meta -->
      <b:if cond='data:view.isMultipleItems'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp'>
          <div class='entry-meta'>
            <b:class cond='data:skin.vars.gridstyle == &quot;1px&quot; and (data:skin.vars.summary == &quot;1px&quot;)' name='has-snip'/>
            <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
            <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
          </div>
        </b:if>
      </b:if>
      <b:if cond='data:view.isPost'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp or data:allBylineItems.share'>
          <b:class name='has-meta'/>
          <div class='entry-meta'>
            <div class='align-left'>
              <b:class cond='data:allBylineItems.timestamp' name='has-time'/>
              <b:if cond='data:allBylineItems.author'><span class='entry-avatar'><span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/></span></b:if>
              <b:tag class='al-items' cond='data:allBylineItems.author and data:allBylineItems.timestamp' name='div'>
              <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
              <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
              </b:tag>
            </div>
            <b:if cond='data:allBylineItems.share'>
              <div class='align-right'>
                <button class='share-toggle btn' expr:aria-label='data:messages.share'/>
              </div>
            </b:if>
          </div>
        </b:if>
      </b:if>
    </b:includable>
            <b:includable id='homePageLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='indexPost' var='post'>
      <!-- Index Post Content -->
      <b:include data='post' name='postFeaturedImage'/>
      <div class='entry-header'>
        <b:include data='post' name='postHeader'/>
        <b:include cond='data:skin.vars.summary == &quot;1px&quot;' data='post' name='postBodySnippet'/>
        <b:include data='post' name='headerByline'/>
      </div>
    </b:includable>
            <b:includable id='inlineAd' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='itemPost' var='post'>
      <!-- Item Post Content -->
      <b:include data='post' name='postMeta'/>
      <div class='item-post-inner flex-col'>
        <div class='entry-header p-eh'>
          <b:include data='post' name='postHeader'/>
        </div>
        <div class='entry-content-wrap flex-col'>
          <b:include data='post' name='postBody'/>
          <b:include cond='data:view.isPost and data:allBylineItems.labels' data='post' name='postLabels'/>
        </div>
        <b:include cond='data:view.isPost and data:allBylineItems.share' data='post' name='postShareButtons'/>
      </div>
      <b:include cond='data:view.isPost' data='post' name='postFooter'/>
    </b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='nextPageLink'>
      <b:if cond='data:olderPageUrl'>
        <a class='post-nav-link post-nav-older-link' expr:href='data:olderPageUrl.canonical'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-older-link'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='post' var='post'>
      <!-- Index Posts -->
      <b:if cond='data:view.isMultipleItems'>
        <b:include data='post' name='indexPost'/>
      </b:if>
      <!-- Item Post -->
      <b:if cond='data:view.isSingleItem'>
        <b:include data='post' name='itemPost'/>
      </b:if>
    </b:includable>
            <b:includable id='postAuthor' var='post'>
      <!-- Post Author -->
      <span class='entry-author mi'><b:if cond='data:allBylineItems.author.label'><span class='by sp'><data:allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span>
    </b:includable>
            <b:includable id='postBody' var='post'> 
      <!-- Ads before post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;xdfcb-main-before-ad&quot;' id='before-ad' name='div'/></b:if>
      <!-- Post Body Entry Content-->
      <div class='post-body entry-content' id='post-body'>
        <data:post.body/>
      </div>
      <!-- Ads after post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;xdfcb-main-after-ad&quot;' id='after-ad' name='div'/></b:if>
    </b:includable>
            <b:includable id='postBodySnippet' var='post'><p class='entry-excerpt excerpt'><b:eval expr='data:post.snippets.long snippet { length: 101 }'/></p></b:includable>
            <b:includable id='postBreadcrumbs' var='post'>
      <!-- Post Breadcrumbs -->
      <b:if cond='data:view.isPost'>
        <b:if cond='data:skin.vars.breadcrumb == &quot;1px&quot;'><nav id='breadcrumb'><a class='home' expr:href='data:blog.homepageUrl'><data:messages.home/></a><b:if cond='data:post.labels'><em class='separator'/><a class='label' expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></b:if></nav></b:if>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.name.jsonEscaped/><b:else/><data:messages.posts/></b:if>&quot;,&quot;item&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.url.canonical.jsonEscaped/><b:else/><b:eval expr='data:blog.homepageUrl.canonical.jsonEscaped + &quot;search/&quot;'/></b:if>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:3,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
      <b:if cond='data:view.isPage'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
    </b:includable>
            <b:includable id='postCategory' var='post'>
      <!-- Post Label -->
      <b:if cond='data:post.labels'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
    </b:includable>
            <b:includable id='postCommentsAndAd' var='post'>
      <article>
        <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;post hentry item-&quot; + data:i : &quot;post hentry item-&quot; + data:i'/>
        <b:class cond='data:view.isSingleItem' name='item-post hentry flex-col'/>
        <b:include data='post' name='post'/>
      </article>
      <b:if cond='data:view.isSingleItem and data:post.allowComments'>
        <!-- Post Comments -->
        <div class='xdfcb-blog-post-comments p-widget' expr:data-shortcode='data:allBylineItems.comments.label contains &quot;type&quot; ? data:allBylineItems.comments.label : &quot;$type={blogger}&quot;'>
          <b:include data='post' name='threadedCommentsDisqus'/>
          <b:include data='post' name='comments'/>
        </div>
      </b:if>
      <!-- Post Navigation -->
      <b:include cond='data:skin.vars.postnav == &quot;1px&quot;' name='postPagination'/>
    </b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postFeaturedImage' var='post'>
      <!-- Post Featured Image -->
      <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/></a>
    </b:includable>
            <b:includable id='postFooter' var='post'>
      <!-- Post Footer Items -->
      <b:tag class='post-footer flex-col' cond='data:post.author.aboutMe or (data:widgets.HTML any w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;)' name='footer'>
        <b:include cond='data:post.author.aboutMe' data='post' name='postFooterAuthorProfile'/>
        <b:include cond='data:widgets.HTML any w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;' data='post' name='relatedPosts'/>
      </b:tag>
    </b:includable>
            <b:includable id='postFooterAuthorProfile' var='post'>
      <div class='about-author p-widget'>
        <div class='author-avatar entry-avatar'>
          <span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/>
        </div>
        <div class='author-description flex-col'>
          <h3 class='author-title'><b:tag cond='data:post.author.profileUrl' expr:alt='data:post.author.name' expr:href='data:post.author.profileUrl' name='a' rel='nofollow noopener' target='_blank'><data:post.author.name/></b:tag></h3>
          <p class='author-text excerpt'><data:post.author.aboutMe/></p>
        </div>
      </div>
    </b:includable>
            <b:includable id='postHeader' var='post'>
      <b:include cond='data:view.isSingleItem' data='post' name='postBreadcrumbs'/>
      <b:include data='post' name='postTitle'/>
      <b:include cond='data:view.isPost' data='post' name='headerByline'/>
    </b:includable>
            <b:includable id='postJumpLink' var='post'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
        <a class='read-more' expr:href='data:post.url.canonical'><data:blog.jumpLinkMessage/></a>
      </b:if>
    </b:includable>
            <b:includable id='postLabels' var='post'>
      <b:if cond='data:post.labels'>
        <div class='entry-labels'>
          <b:if cond='data:allBylineItems.labels.label'><span class='labels-label btn'><data:allBylineItems.labels.label/></span></b:if>
          <b:loop values='data:post.labels' var='label'>
            <a class='label-link btn' expr:href='data:label.url' rel='tag'><data:label.name/></a>
          </b:loop>
        </div>
      </b:if>
    </b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postMeta' var='post'>
      <b:if cond='data:view.isPost'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;NewsArticle&quot;,&quot;mainEntityOfPage&quot;:{&quot;@type&quot;:&quot;WebPage&quot;,&quot;@id&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;},&quot;headline&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;description&quot;:&quot;<data:post.snippets.short.jsonEscaped/>&quot;,&quot;datePublished&quot;:&quot;<data:post.date.iso8601.jsonEscaped/>&quot;,&quot;dateModified&quot;:&quot;<data:post.lastUpdated.iso8601.jsonEscaped/>&quot;,&quot;image&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,<b:if cond='data:post.featuredImage.isResizable'>&quot;url&quot;:&quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:675&quot;)'/>&quot;,&quot;height&quot;:675,&quot;width&quot;:1200<b:else/>&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,&quot;height&quot;:348,&quot;width&quot;:1200</b:if>},&quot;author&quot;:{&quot;@type&quot;:&quot;Person&quot;,&quot;name&quot;:&quot;<data:post.author.name.jsonEscaped/>&quot;},&quot;publisher&quot;:{&quot;@type&quot;:&quot;Organization&quot;,&quot;name&quot;:&quot;Blogger&quot;,&quot;logo&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,&quot;width&quot;:206,&quot;height&quot;:60}}}</script>
      </b:if>
    </b:includable>
            <b:includable id='postMetadataJSONImage'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postMetadataJSONPublisher'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postPagination'>
      <b:if cond='data:view.isPost'>
        <div class='post-nav p-widget'>
          <b:include name='previousPageLink'/>
          <b:include name='nextPageLink'/>
        </div>
      </b:if>
    </b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons' var='post'>
      <!-- Post Share Buttons & Modal -->
      <div class='post-share'>
        <ul class='share-a social color'>
          <li class='share-label'><span class='sl-btn btn'><i class='sl-ico'/></span></li>
          <li class='facebook has-span'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='Facebook'><span>Facebook</span></a></li>
          <li class='twitter has-span'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='nofollow noopener' title='Twitter'><span>Twitter</span></a></li>
          <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='WhatsApp'/></li>
          <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='nofollow noopener' title='Email'/></li>
          <li class='show-more'><button class='btn' expr:aria-label='data:messages.showMore'/></li>
        </ul>
      </div>
    </b:includable>
            <b:includable id='postTimestamp' var='post'>
      <!-- Post Timestamp -->
      <span class='entry-time mi'><b:if cond='data:allBylineItems.author and data:allBylineItems.timestamp.label'><span class='sp'><data:allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span>
    </b:includable>
            <b:includable id='postTitle' var='post'>
      <!-- Post Title Index and Item -->
      <b:if cond='data:view.isMultipleItems'>
        <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle' rel='bookmark'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
      </b:if>
      <b:if cond='data:view.isSingleItem'>
        <h1 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h1>
      </b:if>
    </b:includable>
            <b:includable id='previousPageLink'>
      <b:if cond='data:newerPageUrl'>
        <a class='post-nav-link post-nav-newer-link' expr:href='data:newerPageUrl.canonical'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-newer-link'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
            <b:includable id='relatedPosts' var='post'>
      <!-- Related Posts -->
      <div class='p-widget' id='related-wrap'>
        <div class='title-wrap related-title'>
          <b:with value='data:widgets.HTML filter (w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;) map (w =&gt; w.title)' var='pbtTitle'>
            <h3 class='title'><b:eval expr='data:pbtTitle.first ? data:pbtTitle.first : data:messages.youMayLikeThesePosts'/></h3>
          </b:with>
          <a class='title-link' expr:href='data:post.labels ? data:post.labels.first.url : &quot;/search&quot;'><data:messages.viewAll/></a>
        </div>
        <div class='related-content'>
          <b:if cond='data:post.labels'>
            <div class='related-tag' expr:data-id='data:post.id' expr:data-label='data:post.labels.first.name'/>
            <b:else/>
            <div class='related-tag' data-label='recent' expr:data-id='data:post.id'/>
          </b:if>
        </div> 
      </div>  
    </b:includable>
            <b:includable id='searchMessage'>
      <!-- Search Message -->
      <b:if cond='data:posts.empty'>
        <b:class name='no-posts'/>
      </b:if>
      <b:if cond='data:view.search.query'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'>&quot;<data:view.search.query/>&quot;</span>
            <b:else/>
            <span class='query-info query-success'>&quot;<data:view.search.query/>&quot;</span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.search.label'>
        <div class='queryMessage '>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-label query-error'><data:view.search.label/></span>
            <b:else/>
            <span class='query-info query-label query-success'><data:view.search.label/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isArchive'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'><data:view.archive.rangeMessage/></span>
            <b:else/>
            <span class='query-info query-success'><data:view.archive.rangeMessage/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isError'>
        <div class='errorWrap'>
          <h3>404</h3>
          <h4><data:messages.theresNothingHere/></h4>
          <p><data:navMessage/></p>
          <a class='homepage btn' expr:href='data:blog.homepageUrl'><data:messages.home/></a>
        </div>
      </b:if>
      <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
    </b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentJs' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedComments' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentsDisqus' var='post'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
        </b:section>
        <b:section cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets.HTML any w =&gt; w.sectionId == &quot;xdfcb-related-posts&quot;))' id='xdfcb-related-posts' maxwidgets='1' name='Related Posts' showaddelement='yes'>
          <b:widget id='HTML51' locked='true' title='You might like' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>$results={3}</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
        </b:section>
      </main>
      <aside id='sidebar-wrapper'>
        <b:section class='sidebar pbt-s' cond='!data:view.isError' id='sidebar' name='Sidebar' showaddelement='yes'>
          <b:widget id='LinkList1' locked='false' title='' type='LinkList' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='link-3'>https://github.com/Ajay-Sahani</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='text-1'>youtube</b:widget-setting>
              <b:widget-setting name='link-1'>https://youtube.com/@RAJOOKUMARNISHAD</b:widget-setting>
              <b:widget-setting name='text-0'>{getSocial}</b:widget-setting>
              <b:widget-setting name='link-2'>https://www.instagram.com/ajay._.sahani/</b:widget-setting>
              <b:widget-setting name='text-3'>git hub</b:widget-setting>
              <b:widget-setting name='link-0'>#</b:widget-setting>
              <b:widget-setting name='text-2'>instagram</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='PopularPosts2' locked='false' title='Popular Posts' type='PopularPosts' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:class expr:name='data:widget.sectionId == &quot;sidebar&quot; ? &quot;popular-items&quot; : &quot;default-items&quot;'/>
        <b:loop index='i' values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
          <b:widget id='Label1' locked='false' title='Categories' type='Label' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>LIST</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'>carpentery,fishhook,oil lamp,pottery,stone tools</b:widget-setting>
              <b:widget-setting name='showType'>USER_SELECTED</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
            <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
          </b:widget>
          <b:widget id='Label2' locked='false' title='Main Tags' type='Label' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>CLOUD</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
            <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
          </b:widget>
          <b:widget id='Header1' locked='false' title='help others (Header)' type='Header' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEibOLhEQf5WybUGqqDTDm8Mx0uOFFOtXCP7jWoazegkJX1o9-GuJgU3OpWjAvGJsfNlPoZgqS-r_pllSdX-By2d_i5-fn4VxvWGZiAYpRwgE_aUBS00EuyVstEiiwilpRStSWCWeRdy34h7TNpMJdA50nKGfmP9Ns4lNBVT2segk81lEFr4wNWAm4s8vw=s150</b:widget-setting>
              <b:widget-setting name='displayHeight'>150</b:widget-setting>
              <b:widget-setting name='sectionWidth'>150</b:widget-setting>
              <b:widget-setting name='useImage'>true</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
              <b:widget-setting name='imagePlacement'>BEFORE_DESCRIPTION</b:widget-setting>
              <b:widget-setting name='displayWidth'>150</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
    </b:includable>
            <b:includable id='behindImageStyle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='description'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='image'>
      <a class='logo-img' expr:href='data:blog.homepageUrl.canonical'>
        <img expr:alt='data:blog.title.escaped' expr:height='data:height' expr:src='data:image' expr:title='data:blog.title.escaped' expr:width='data:width'/>
        <b:if cond='data:view.isMultipleItems'><b:if cond='data:widget.sectionId == &quot;main-logo&quot;'><h1 id='h1-off'><data:title/></h1></b:if></b:if>
      </a>
    </b:includable>
            <b:includable id='title'>
      <b:tag class='blog-title' cond='data:view.isMultipleItems' name='h1'>
        <b:tag class='blog-title' cond='!data:view.isMultipleItems' name='span'>
          <b:tag expr:href='data:blog.homepageUrl.canonical' name='a'>
            <data:title/>
          </b:tag>
        </b:tag>
      </b:tag>
    </b:includable>
          </b:widget>
          <b:widget id='Attribution1' locked='false' title='' type='Attribution' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='copyright'/>
            </b:widget-settings>
            <b:includable id='main' var='this'>
  <div class='widget-content'>
    <div class='blogger'>
      <a expr:href='data:bloggerUrl' rel='nofollow'>
        <b:include name='flatBloggerIcon'/>
        <b:message name='messages.poweredByBlogger'/>
      </a>
    </div>

    <b:if cond='data:imageAuthor'>
      <div class='image-attribution'>
        <b:if cond='data:imageAuthor.url'>
          <b:message name='messages.templateImagesByLink'>
            <b:param expr:value='data:imageAuthor.url'/>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        <b:else/>
          <b:message name='messages.templateImagesBy'>
            <b:param expr:value='data:imageAuthor.name'/>
          </b:message>
        </b:if>
      </div>
    </b:if>

    <b:if cond='data:copyright != &quot;&quot;'>
      <div class='copyright'><data:copyright/></div>
    </b:if>
  </div>
</b:includable>
          </b:widget>
          <b:widget id='BlogArchive1' locked='false' title='' type='BlogArchive' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showStyle'>FLAT</b:widget-setting>
              <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
              <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
              <b:widget-setting name='monthPattern'>MMMM yyyy</b:widget-setting>
              <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
              <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
              <b:widget-setting name='chronological'>false</b:widget-setting>
              <b:widget-setting name='showPosts'>true</b:widget-setting>
              <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class name='archive-list'/>
        <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;, &quot;HIERARCHY&quot;}' name='flat'/>
      </div>
    </b:includable>
            <b:includable id='flat'>
      <ul class='list-style'>
        <b:loop values='data:data' var='i'>
          <li><a class='archive-name' expr:href='data:i.url'><data:i.name/><b:if cond='data:i.post-count'><b:class name='has-count'/><span class='archive-count count-style'>(<data:i.post-count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
            <b:includable id='hierarchy'>
  <b:include data='data' name='interval'/>
</b:includable>
            <b:includable id='interval' var='intervals'>
  <ul class='hierarchy'>
    <b:loop values='data:intervals' var='interval'>
      <li class='archivedate'>
        <div class='hierarchy-title'>
          <a class='post-count-link' expr:href='data:interval.url'>
            <data:interval.name/>
            <span class='post-count'><data:interval.post-count/></span>
          </a>
        </div>
        <div class='hierarchy-content'>
          <b:include cond='data:interval.data' data='interval.data' name='interval'/>
          <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
            <b:includable id='posts' var='posts'>
  <ul class='posts hierarchy'>
    <b:loop values='data:posts' var='post'>
      <li>
        <a expr:href='data:post.url'><data:post.title/></a>
      </li>
    </b:loop>
  </ul>
</b:includable>
          </b:widget>
          <b:widget id='ReportAbuse1' locked='false' title='' type='ReportAbuse' visible='true'>
            <b:includable id='main'>
  <b:include name='reportAbuse'/>
</b:includable>
          </b:widget>
          <b:widget cond='data:view.isSingleItem and data:posts any (p =&gt; p.id != data:view.postId)' id='PopularPosts1' locked='false' title='' type='PopularPosts' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:class expr:name='data:widget.sectionId == &quot;sidebar&quot; ? &quot;popular-items&quot; : &quot;default-items&quot;'/>
        <b:loop index='i' values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
          <b:widget cond='!data:view.isPost' id='PageList1' locked='false' title='' type='PageList' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='pageListJson'><![CDATA[{"link0":{"href":"http://ourancientearth.blogspot.com/","position":0,"title":"Home"}}]]></b:widget-setting>
              <b:widget-setting name='homeTitle'>Home</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='pagelist-content'/>
    </b:includable>
            <b:includable id='overflowButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='overflowablePageList'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='pageLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='pageList'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
          <b:widget id='Profile1' locked='false' title='About Me' type='Profile' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showaboutme'>true</b:widget-setting>
              <b:widget-setting name='showlocation'>true</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='authorProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' expr:src='resizeImage(data:authorPhoto.image, 50, &quot;1:1&quot;)'/>
    </b:includable>
            <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
            <b:includable id='defaultProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' src='https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/w50-h50-p-k-no-nu/avatar.jpg'/>
    </b:includable>
            <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
            <b:includable id='teamProfile'>
  <ul>
    <b:loop values='data:authors' var='author'>
      <li>
        <div class='team-member'>
          <b:include data='author' name='teamProfileLink'/>
        </div>
      </li>
    </b:loop>
  </ul>
</b:includable>
            <b:includable id='teamProfileLink' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:display-name/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
            <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
            <b:includable id='userProfile' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:displayname/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
            <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
            <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
            <b:includable id='userProfileInfo' var='this'>
      <div class='profile-info'>
        <dl class='profile-datablock'>
          <b:include name='userProfileData'/>
        </dl>
        <b:include name='viewProfileLink'/>
      </div>
    </b:includable>
            <b:includable id='userProfileText'>
  <dd class='profile-textblock'>
    <data:aboutme/>
  </dd>
</b:includable>
            <b:includable id='viewProfileLink'>
  <a class='profile-link' expr:href='data:userUrl' rel='author nofollow'>
    <data:messages.viewMyCompleteProfile/>
  </a>
</b:includable>
          </b:widget>
          <b:widget id='PageList2' locked='false' title='' type='PageList' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='pageListJson'><![CDATA[{"link0":{"href":"http://ourancientearth.blogspot.com/","position":0,"title":"Home"}}]]></b:widget-setting>
              <b:widget-setting name='homeTitle'>Home</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='pagelist-content'/>
    </b:includable>
            <b:includable id='overflowButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='overflowablePageList'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='pageLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='pageList'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
          <b:widget cond='data:view.isHomepage' id='FeaturedPost1' locked='false' title='' type='FeaturedPost' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showSnippet'>true</b:widget-setting>
              <b:widget-setting name='showPostTitle'>true</b:widget-setting>
              <b:widget-setting name='postId'>0</b:widget-setting>
              <b:widget-setting name='showFirstImage'>true</b:widget-setting>
              <b:widget-setting name='useMostRecentPost'>true</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='featured-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
        </b:section>
      </aside>
    </div>
  </div>
  <footer class='flex-col' id='footer-wrapper'>
    <b:if cond='data:view.isLayoutMode or (data:widgets.Image any w =&gt; w.sectionId == &quot;xdfcb-about-section&quot;)'>
      <div class='primary-footer flex-c'>
        <b:class cond='data:skin.vars.footer_bg == data:skin.vars.footerbar_bg' name='has-border'/>
        <div class='container row-x1'>
          <b:section class='about-section flex-sb' cond='data:widgets.Image any w =&gt; w.sectionId == &quot;xdfcb-about-section&quot;' id='xdfcb-about-section' maxwidgets='2' name='About Section' showaddelement='yes'>
            <b:widget id='Image51' locked='true' title='About Us' type='Image' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEhfvHBT15uJvMtrDrlfZVwt-uqMGTYnALNpOG_3UbxFx6IQ7fFi2x7IrGIRla8Jon8RLwzq2HQZP_QCurerR1t8RvF8wsUSlbZcpz_rEEiX3vQJ0oBAeZBKTVYxvcPuf47HMQWUVf4I1jcjp5MSV3mxzraOGmAk0om3gDk-_7v2FcJ2mjsFlCFCnBJCnQ=s150</b:widget-setting>
                <b:widget-setting name='displayHeight'>150</b:widget-setting>
                <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
                <b:widget-setting name='displayWidth'>150</b:widget-setting>
                <b:widget-setting name='link'>https://ourancientearth.blogspot.com/p/about-us.html</b:widget-setting>
                <b:widget-setting name='caption'>Creativity is thinking up new things. Innovation is doing new things.</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
              <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
            </b:widget>
            <b:widget id='LinkList203' locked='true' title='Follow Us' type='LinkList' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='link-3'>https://github.com/Ajay-Sahani</b:widget-setting>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='text-1'>youtube</b:widget-setting>
                <b:widget-setting name='link-1'>https://youtube.com/@RAJOOKUMARNISHAD</b:widget-setting>
                <b:widget-setting name='text-0'>{getSocial}</b:widget-setting>
                <b:widget-setting name='link-2'>https://instagram.com/ajay._.sahani?igshid=YmMyMTA2M2Y=</b:widget-setting>
                <b:widget-setting name='text-3'>git hub</b:widget-setting>
                <b:widget-setting name='link-0'>#</b:widget-setting>
                <b:widget-setting name='text-2'>instagram</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
              <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
            </b:widget>
          </b:section>
        </div>
      </div>
    </b:if>
    <div class='footer-bar flex-c'>
      <div class='container row-x1 flex-sb'>
        <div class='footer-copyright' id='footer-copyright'>
          <span class='copyright-text'>Design by - <a href='https://probloggertemplates.com/' id='probtemplates' title='Pro Blogger Templates'>Blogger Templates</a> | Distributed by <a href='https://www.bloggertemplate.org/' rel='dofollow'> Blogger Templates</a></span>
        </div>
        <b:section class='footer-menu' id='footer-menu' maxwidgets='1' name='Footer Menu' showaddelement='yes'>
          <b:widget id='LinkList204' locked='true' title='' type='LinkList' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='link-3'>https://ourancientearth.blogspot.com/p/contact-us.html</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='text-1'>About Us</b:widget-setting>
              <b:widget-setting name='link-1'>https://ourancientearth.blogspot.com/p/about-us.html</b:widget-setting>
              <b:widget-setting name='text-0'>Home</b:widget-setting>
              <b:widget-setting name='link-2'>https://ourancientearth.blogspot.com/p/privacy-policy.html</b:widget-setting>
              <b:widget-setting name='text-3'>Contact Us</b:widget-setting>
              <b:widget-setting name='link-0'>https://ourancientearth.blogspot.com/</b:widget-setting>
              <b:widget-setting name='text-2'>Privacy Policy</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
          </b:widget>
        </b:section>
      </div>
    </div>
  </footer>
</div>
<!-- Fixed Elements -->
<div id='fixed-elements'>
  <b:include cond='data:view.isPost' name='pbt-share-modal'/>
  <div id='slide-menu'>
    <div class='slide-menu-header'>
      <div class='mobile-logo'/>
      <button aria-label='Hide Menu' class='hide-mobile-menu'/>
    </div>
    <div class='slide-menu-flex'>
      <div class='mobile-menu' id='mobile-menu'/>
      <div class='mm-footer'/>
    </div>
  </div>
  <div class='overlay' id='overlay'/>
  <button aria-label='Back To Top' class='btn' id='back-top'/>
</div>
<b:if cond='data:view.isSingleItem'>
  <b:section class='hidden-widgets' deleted='true' id='hidden-widgets' maxwidgets='1' showaddelement='no'>
    <b:widget id='ContactForm1' locked='true' title='Contact Form' type='ContactForm' visible='true'>
      <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
      <b:includable id='content'>
      <b:include name='contact-form-content'/>
    </b:includable>
    </b:widget>
  </b:section>
</b:if>
<!-- Main Scripts -->
<b:tag name='script' src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js' type='text/javascript'/>
<b:include name='theme-variables'/>
<b:tag name='script' type='text/javascript'>
//<![CDATA[
/*! Theia Sticky Sidebar | v1.5.0 - https://github.com/WeCodePixels/theia-sticky-sidebar */
!function(i){i.fn.theiaStickySidebar=function(t){var e,o,a,s,n;function d(t,e){return!0===t.initialized||!(i("body").width()<t.minWidth)&&(function(t,e){t.initialized=!0,0===i("#theia-sticky-sidebar-stylesheet-"+t.namespace).length&&i("head").append(i('<style id="theia-sticky-sidebar-stylesheet-'+t.namespace+'">.theiaStickySidebar:after {content: ""; display: table; clear: both;}</style>')),e.each(function(){var e={};if(e.sidebar=i(this),e.options=t||{},e.container=i(e.options.containerSelector),0==e.container.length&&(e.container=e.sidebar.parent()),e.sidebar.parent().css("-webkit-transform","none"),e.sidebar.css({position:e.options.defaultPosition,overflow:"visible","-webkit-box-sizing":"border-box","-moz-box-sizing":"border-box","box-sizing":"border-box"}),e.stickySidebar=e.sidebar.find(".theiaStickySidebar"),0==e.stickySidebar.length){var o=/(?:text|application)\/(?:x-)?(?:javascript|ecmascript)/i;e.sidebar.find("script").filter(function(i,t){return 0===t.type.length||t.type.match(o)}).remove(),e.stickySidebar=i("<div>").addClass("theiaStickySidebar").append(e.sidebar.children()),e.sidebar.append(e.stickySidebar)}e.marginBottom=parseInt(e.sidebar.css("margin-bottom")),e.paddingTop=parseInt(e.sidebar.css("padding-top")),e.paddingBottom=parseInt(e.sidebar.css("padding-bottom"));var a,s,n,d=e.stickySidebar.offset().top,c=e.stickySidebar.outerHeight();function p(){e.fixedScrollTop=0,e.sidebar.css({"min-height":"1px"}),e.stickySidebar.css({position:"static",width:"",transform:"none"})}e.stickySidebar.css("padding-top",1),e.stickySidebar.css("padding-bottom",1),d-=e.stickySidebar.offset().top,c=e.stickySidebar.outerHeight()-c-d,0==d?(e.stickySidebar.css("padding-top",0),e.stickySidebarPaddingTop=0):e.stickySidebarPaddingTop=1,0==c?(e.stickySidebar.css("padding-bottom",0),e.stickySidebarPaddingBottom=0):e.stickySidebarPaddingBottom=1,e.previousScrollTop=null,e.fixedScrollTop=0,p(),e.onScroll=function(e){if(e.stickySidebar.is(":visible"))if(i("body").width()<e.options.minWidth)p();else{if(e.options.disableOnResponsiveLayouts)if(e.sidebar.outerWidth("none"==e.sidebar.css("float"))+50>e.container.width())return void p();var o,a,s=i(document).scrollTop(),n="static";if(s>=e.sidebar.offset().top+(e.paddingTop-e.options.additionalMarginTop)){var d,c=e.paddingTop+t.additionalMarginTop,b=e.paddingBottom+e.marginBottom+t.additionalMarginBottom,l=e.sidebar.offset().top,h=e.sidebar.offset().top+(o=e.container,a=o.height(),o.children().each(function(){a=Math.max(a,i(this).height())}),a),f=0+t.additionalMarginTop;d=e.stickySidebar.outerHeight()+c+b<i(window).height()?f+e.stickySidebar.outerHeight():i(window).height()-e.marginBottom-e.paddingBottom-t.additionalMarginBottom;var g=l-s+e.paddingTop,S=h-s-e.paddingBottom-e.marginBottom,m=e.stickySidebar.offset().top-s,y=e.previousScrollTop-s;"fixed"==e.stickySidebar.css("position")&&"modern"==e.options.sidebarBehavior&&(m+=y),"stick-to-top"==e.options.sidebarBehavior&&(m=t.additionalMarginTop),"stick-to-bottom"==e.options.sidebarBehavior&&(m=d-e.stickySidebar.outerHeight()),m=0<y?Math.min(m,f):Math.max(m,d-e.stickySidebar.outerHeight()),m=Math.max(m,g),m=Math.min(m,S-e.stickySidebar.outerHeight());var u=e.container.height()==e.stickySidebar.outerHeight();n=!u&&m==f||!u&&m==d-e.stickySidebar.outerHeight()?"fixed":s+m-e.sidebar.offset().top-e.paddingTop<=t.additionalMarginTop?"static":"absolute"}if("fixed"==n){var k=i(document).scrollLeft();e.stickySidebar.css({position:"fixed",width:r(e.stickySidebar)+"px",transform:"translateY("+m+"px)",left:e.sidebar.offset().left+parseInt(e.sidebar.css("padding-left"))-k+"px",top:"0px"})}else if("absolute"==n){var v={};"absolute"!=e.stickySidebar.css("position")&&(v.position="absolute",v.transform="translateY("+(s+m-e.sidebar.offset().top-e.stickySidebarPaddingTop-e.stickySidebarPaddingBottom)+"px)",v.top="0px"),v.width=r(e.stickySidebar)+"px",v.left="",e.stickySidebar.css(v)}else"static"==n&&p();"static"!=n&&1==e.options.updateSidebarHeight&&e.sidebar.css({"min-height":e.stickySidebar.outerHeight()+e.stickySidebar.offset().top-e.sidebar.offset().top+e.paddingBottom}),e.previousScrollTop=s}},e.onScroll(e),i(document).on("scroll."+e.options.namespace,(a=e,function(){a.onScroll(a)})),i(window).on("resize."+e.options.namespace,(s=e,function(){s.stickySidebar.css({position:"static"}),s.onScroll(s)})),"undefined"!=typeof ResizeSensor&&new ResizeSensor(e.stickySidebar[0],(n=e,function(){n.onScroll(n)}))})}(t,e),!0)}function r(i){var t;try{t=i[0].getBoundingClientRect().width}catch(i){}return void 0===t&&(t=i.width()),t}return(t=i.extend({containerSelector:"",additionalMarginTop:0,additionalMarginBottom:0,updateSidebarHeight:!0,minWidth:0,disableOnResponsiveLayouts:!0,sidebarBehavior:"modern",defaultPosition:"relative",namespace:"TSS"},t)).additionalMarginTop=parseInt(t.additionalMarginTop)||0,t.additionalMarginBottom=parseInt(t.additionalMarginBottom)||0,d(e=t,this)||(console.log("TSS: Body width smaller than options.minWidth. Init is delayed."),i(document).on("scroll."+e.namespace,(s=e,n=this,function(t){d(s,n)&&i(this).unbind(t)})),i(window).on("resize."+e.namespace,(o=e,a=this,function(t){d(o,a)&&i(this).unbind(t)}))),this}}(jQuery);

/*! pbtMenu by Pro Blogger Templates | v1.3.0 - https://probloggertemplates.com */
!function(e){e.fn.pbtMenu=function(){return this.each(function(){for(var t=e(this),a=t.find(".widget ul > li").children("a"),n=a.length,r=0;r<n;r++){var i=a.eq(r),s=i.text();if("_"!==s.charAt(0))if("_"===a.eq(r+1).text().charAt(0)){var u=i.parent();u.append('<ul class="sub-menu sm-1"/>')}"_"===s.charAt(0)&&(i.text(s.replace("_","")),i.parent().appendTo(u.children(".sub-menu")))}for(r=0;r<n;r++){var c=a.eq(r),d=c.text();if("_"!==d.charAt(0))if("_"===a.eq(r+1).text().charAt(0)){var p=c.parent();p.append('<ul class="sub-menu sm-2"/>')}"_"===d.charAt(0)&&(c.text(d.replace("_","")),c.parent().appendTo(p.children(".sm-2")))}t.find(".sub-menu").parent("li").addClass("has-sub"),t.children(".widget").addClass("is-ready")})}}(jQuery);

/*! pbtLazy by Pro Blogger Templates | v1.4.0 - https://probloggertemplates.com */
!function(o){o.fn.pbtLazy=function(n){return n=o.extend({onScroll:!0},n),this.each(function(t,c,e){var r=o(this),a=o(window),h=r.data("src"),l=r.width()>=1?r.width():1,s=(l=Math.round(l+l/10),r.height()>=1?r.height():1),i="w"+l+"-h"+(s=Math.round(s+s/10))+"-p-k-no-nu";function u(){var o=new Image;o.onload=function(){r.attr("style","background-image:url("+this.src+")").addClass("pbt-lazy")},o.src=t}h.match("resources.blogblog.com")&&(h="undefined"!=typeof noThumbnail?noThumbnail:"//1.bp.blogspot.com/-rI4UCIrwEI4/YN3nGkf0nCI/AAAAAAAAAD0/DQ6fW7eCps8NL7S0oh374KFg1MsWUf2GQCLcBGAsYHQ/s72-c/ptb-nth.png"),h.match(".googleusercontent.com")&&h.match("=")&&(e=h.split("="),h=e[1]&&""!=e[1].trim()?e[0]+"=w72-h72-p-k-no-nu":h),h.match(".googleusercontent.com")&&!h.match("=")&&(h+="=w72-h72-p-k-no-nu"),t=h.match("/s72-c")?h.replace("/s72-c","/"+i):h.match("/w72-h")?h.replace("/w72-h72-p-k-no-nu","/"+i):h.match("=w72-h")?h.replace("=w72-h72-p-k-no-nu","="+i):h,1==n.onScroll?a.on("load resize scroll",function o(){a.scrollTop()+a.height()>=r.offset().top&&(a.off("load resize scroll",o),u())}).trigger("scroll"):a.on("load",function o(){a.off("load",o),u()}).trigger("load")})}}(jQuery);

/*! jQuery replaceText | v1.1.0 - https://benalman.com/projects/jquery-replacetext-plugin */
!function(e){e.fn.replaceText=function(n,t,i){return this.each(function(){var o,r,l=this.firstChild,u=[];if(l)do{3===l.nodeType&&(r=(o=l.nodeValue).replace(n,t))!==o&&(!i&&/</.test(r)?(e(l).before(r),u.push(l)):l.nodeValue=r)}while(l=l.nextSibling);u.length&&e(u).remove()})}}(jQuery);
//]]>
</b:tag>
<b:tag name='script' type='text/javascript'>
//<![CDATA[
var _$_pbt3=["\x51\x20\x61\x24\x65\x3D\x5B\x22\x5C\x31\x54\x22\x2C\x22\x5C\x69\x5C\x75\x5C\x6A\x5C\x6B\x5C\x64\x22\x2C\x22\x5C\x6A\x5C\x63\x5C\x6E\x5C\x46\x5C\x64\x5C\x47\x22\x2C\x22\x5C\x4C\x22\x2C\x22\x5C\x64\x5C\x6C\x5C\x6B\x5C\x72\x22\x2C\x22\x5C\x72\x5C\x66\x5C\x64\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6C\x5C\x6C\x5C\x68\x5C\x6C\x5C\x71\x5C\x72\x5C\x69\x5C\x46\x5C\x44\x5C\x4F\x5C\x4E\x5C\x7A\x5C\x4F\x5C\x31\x5A\x5C\x6C\x5C\x6C\x5C\x68\x5C\x6C\x5C\x31\x66\x5C\x4E\x5C\x4A\x5C\x7A\x5C\x4F\x5C\x32\x71\x5C\x6E\x5C\x7A\x5C\x69\x5C\x75\x5C\x31\x65\x22\x2C\x22\x5C\x6E\x5C\x68\x5C\x33\x63\x5C\x63\x5C\x69\x5C\x42\x5C\x6A\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x6A\x5C\x68\x5C\x66\x5C\x79\x5C\x63\x5C\x6C\x5C\x44\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x22\x2C\x22\x5C\x4A\x5C\x4B\x5C\x63\x5C\x63\x5C\x79\x5C\x69\x5C\x4A\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x5C\x4A\x5C\x79\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x5C\x33\x62\x5C\x66\x5C\x6A\x5C\x64\x5C\x4C\x5C\x31\x46\x5C\x69\x5C\x68\x5C\x6E\x5C\x32\x71\x5C\x72\x5C\x66\x5C\x54\x5C\x71\x5C\x6C\x5C\x63\x5C\x69\x5C\x42\x5C\x6A\x5C\x64\x5C\x69\x5C\x4C\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x70\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x4A\x5C\x4B\x5C\x63\x5C\x63\x5C\x79\x5C\x69\x5C\x4A\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x5C\x4A\x5C\x79\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x5C\x4A\x5C\x71\x5C\x4A\x22\x2C\x22\x5C\x33\x62\x5C\x66\x5C\x6A\x5C\x64\x5C\x4C\x5C\x31\x46\x5C\x69\x5C\x68\x5C\x6E\x5C\x32\x71\x5C\x72\x5C\x66\x5C\x54\x5C\x71\x5C\x6C\x5C\x63\x5C\x69\x5C\x42\x5C\x6A\x5C\x64\x5C\x69\x5C\x4C\x22\x2C\x22\x5C\x4A\x5C\x4B\x5C\x63\x5C\x63\x5C\x79\x5C\x69\x5C\x4A\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x5C\x4A\x5C\x79\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x5C\x33\x62\x5C\x66\x5C\x6A\x5C\x64\x5C\x4C\x5C\x31\x46\x5C\x69\x5C\x68\x5C\x6E\x5C\x32\x71\x5C\x72\x5C\x66\x5C\x54\x5C\x71\x5C\x6C\x5C\x63\x5C\x69\x5C\x42\x5C\x6A\x5C\x64\x5C\x69\x5C\x4C\x22\x2C\x22\x5C\x31\x54\x5C\x64\x22\x2C\x22\x5C\x6B\x5C\x79\x22\x2C\x22\x5C\x75\x5C\x68\x5C\x75\x22\x2C\x22\x5C\x71\x22\x2C\x22\x22\x2C\x22\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x66\x5C\x6A\x5C\x64\x5C\x63\x5C\x6C\x5C\x6E\x5C\x66\x5C\x64\x5C\x63\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x6A\x22\x2C\x22\x5C\x47\x5C\x6C\x5C\x63\x5C\x4B\x22\x2C\x22\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x6E\x5C\x68\x5C\x31\x7A\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x31\x6A\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x31\x53\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x69\x5C\x75\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x31\x6A\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x41\x5C\x72\x5C\x6B\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x71\x5C\x6E\x5C\x66\x5C\x72\x5C\x63\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x6E\x5C\x66\x5C\x72\x5C\x63\x22\x2C\x22\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x4F\x22\x2C\x22\x5C\x42\x5C\x6E\x5C\x79\x5C\x63\x5C\x4B\x5C\x6B\x5C\x6E\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x31\x56\x5C\x66\x5C\x6E\x5C\x42\x5C\x66\x5C\x6C\x5C\x4D\x22\x2C\x22\x5C\x33\x68\x5C\x63\x5C\x7A\x5C\x6C\x5C\x42\x5C\x66\x5C\x6C\x5C\x4D\x22\x2C\x22\x5C\x31\x4A\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x31\x6A\x5C\x75\x5C\x6C\x5C\x6B\x5C\x6A\x22\x2C\x22\x5C\x31\x4A\x5C\x66\x5C\x4D\x22\x2C\x22\x5C\x31\x56\x5C\x42\x5C\x6E\x5C\x63\x22\x2C\x22\x5C\x31\x56\x5C\x42\x5C\x6A\x5C\x4D\x22\x2C\x22\x5C\x31\x6A\x5C\x42\x5C\x46\x5C\x42\x5C\x69\x5C\x64\x22\x2C\x22\x5C\x31\x42\x5C\x63\x5C\x75\x5C\x64\x5C\x63\x5C\x72\x5C\x7A\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x32\x6A\x5C\x70\x5C\x64\x5C\x68\x5C\x7A\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x32\x72\x5C\x68\x5C\x50\x5C\x63\x5C\x72\x5C\x7A\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x31\x4E\x5C\x63\x5C\x70\x5C\x63\x5C\x72\x5C\x7A\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x31\x68\x5C\x72\x5C\x31\x67\x5C\x41\x5C\x31\x68\x5C\x79\x5C\x31\x67\x5C\x31\x6B\x5C\x41\x5C\x31\x68\x5C\x4D\x5C\x31\x67\x22\x2C\x22\x5C\x75\x5C\x42\x5C\x7A\x5C\x6A\x5C\x6B\x5C\x69\x5C\x47\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x69\x5C\x42\x5C\x7A\x5C\x69\x5C\x64\x5C\x6C\x5C\x6B\x5C\x6E\x5C\x46\x22\x2C\x22\x5C\x31\x68\x5C\x4D\x5C\x31\x67\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x66\x5C\x70\x5C\x63\x22\x2C\x22\x5C\x31\x68\x5C\x79\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x72\x5C\x31\x67\x22\x2C\x22\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x31\x4E\x5C\x66\x5C\x64\x5C\x63\x5C\x31\x53\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x22\x2C\x22\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x31\x4E\x5C\x66\x5C\x64\x5C\x63\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x41\x5C\x72\x5C\x6B\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x75\x5C\x42\x5C\x7A\x5C\x6A\x5C\x6B\x5C\x69\x5C\x47\x5C\x63\x5C\x79\x5C\x44\x5C\x41\x5C\x79\x5C\x66\x5C\x64\x5C\x63\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x44\x5C\x4F\x5C\x4E\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x75\x5C\x42\x5C\x7A\x5C\x6A\x5C\x6B\x5C\x69\x5C\x47\x5C\x63\x5C\x79\x5C\x44\x5C\x41\x5C\x79\x5C\x66\x5C\x64\x5C\x63\x5C\x64\x5C\x6B\x5C\x72\x5C\x63\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x72\x5C\x63\x5C\x64\x5C\x66\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x22\x2C\x22\x5C\x69\x5C\x6C\x5C\x70\x22\x2C\x22\x5C\x66\x5C\x64\x5C\x64\x5C\x6C\x22\x2C\x22\x5C\x4B\x5C\x6B\x5C\x6C\x5C\x69\x5C\x64\x22\x2C\x22\x5C\x6B\x5C\x72\x5C\x46\x22\x2C\x22\x5C\x4B\x5C\x6B\x5C\x6E\x5C\x79\x22\x2C\x22\x5C\x47\x5C\x64\x5C\x72\x5C\x6A\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x22\x2C\x22\x5C\x4A\x22\x2C\x22\x5C\x69\x5C\x6A\x5C\x6B\x5C\x70\x5C\x63\x22\x2C\x22\x5C\x4A\x5C\x79\x22\x2C\x22\x5C\x4A\x5C\x55\x5C\x32\x74\x5C\x31\x79\x5C\x71\x5C\x47\x5C\x32\x74\x5C\x31\x79\x5C\x71\x5C\x75\x5C\x71\x5C\x31\x62\x5C\x71\x5C\x6E\x5C\x68\x5C\x71\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x72\x5C\x63\x5C\x79\x5C\x6B\x5C\x66\x5C\x31\x54\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x22\x2C\x22\x5C\x42\x5C\x6C\x5C\x6A\x22\x2C\x22\x5C\x47\x5C\x64\x5C\x64\x5C\x75\x5C\x69\x5C\x31\x66\x5C\x4A\x5C\x4A\x5C\x6C\x5C\x63\x5C\x69\x5C\x68\x5C\x42\x5C\x6C\x5C\x70\x5C\x63\x5C\x69\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x5C\x6B\x5C\x72\x5C\x46\x5C\x4A\x5C\x7A\x5C\x6A\x5C\x66\x5C\x6E\x5C\x31\x62\x5C\x45\x5C\x46\x5C\x6B\x5C\x4B\x22\x2C\x22\x5C\x6B\x5C\x6E\x5C\x79\x5C\x63\x5C\x54\x5C\x32\x6A\x5C\x4B\x22\x2C\x22\x5C\x4E\x5C\x6B\x5C\x72\x5C\x46\x22\x2C\x22\x5C\x4A\x5C\x79\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x5C\x45\x22\x2C\x22\x5C\x4A\x5C\x72\x5C\x66\x5C\x54\x5C\x6C\x5C\x63\x5C\x69\x5C\x79\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x5C\x45\x22\x2C\x22\x5C\x6B\x5C\x72\x5C\x46\x5C\x45\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x22\x2C\x22\x5C\x6B\x5C\x45\x5C\x4D\x5C\x64\x5C\x6B\x5C\x72\x5C\x46\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x22\x2C\x22\x5C\x41\x5C\x6B\x5C\x69\x5C\x71\x5C\x4D\x5C\x64\x5C\x6B\x5C\x72\x5C\x46\x22\x2C\x22\x5C\x70\x5C\x66\x5C\x64\x5C\x63\x5C\x46\x5C\x68\x5C\x6C\x5C\x4D\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x70\x5C\x66\x5C\x64\x5C\x63\x5C\x46\x5C\x68\x5C\x6C\x5C\x4D\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x64\x5C\x63\x5C\x6C\x5C\x72\x22\x2C\x22\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x31\x7A\x5C\x66\x5C\x46\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x41\x5C\x6B\x5C\x64\x5C\x63\x5C\x72\x5C\x71\x22\x2C\x22\x5C\x44\x5C\x4F\x5C\x4E\x5C\x66\x5C\x41\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x5C\x41\x5C\x69\x5C\x31\x71\x5C\x71\x5C\x31\x47\x22\x2C\x22\x5C\x44\x5C\x41\x5C\x47\x5C\x6C\x5C\x63\x5C\x4B\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x4F\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x5C\x44\x5C\x41\x5C\x79\x5C\x66\x5C\x64\x5C\x66\x5C\x71\x5C\x69\x5C\x6C\x5C\x70\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x66\x5C\x4F\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x47\x5C\x63\x5C\x66\x5C\x79\x5C\x63\x5C\x6C\x5C\x44\x5C\x4F\x5C\x4E\x5C\x47\x5C\x31\x79\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x44\x5C\x4F\x5C\x4E\x5C\x66\x5C\x41\x5C\x47\x5C\x6C\x5C\x63\x5C\x4B\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x41\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x66\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x47\x5C\x31\x79\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x69\x5C\x75\x5C\x68\x5C\x6E\x5C\x69\x5C\x63\x5C\x31\x56\x5C\x31\x42\x5C\x32\x6A\x5C\x32\x72\x22\x2C\x22\x5C\x33\x46\x5C\x31\x5A\x5C\x31\x7A\x22\x2C\x22\x5C\x31\x46\x5C\x69\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x66\x5C\x31\x46\x5C\x66\x5C\x54\x22\x2C\x22\x5C\x42\x5C\x6E\x5C\x6A\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x64\x5C\x4D\x5C\x75\x5C\x63\x5C\x71\x22\x2C\x22\x5C\x66\x5C\x79\x5C\x79\x5C\x31\x77\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x75\x5C\x66\x5C\x6C\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x6B\x5C\x64\x5C\x63\x5C\x72\x5C\x69\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x22\x2C\x22\x5C\x4B\x5C\x63\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x69\x5C\x75\x5C\x6A\x5C\x6B\x5C\x70\x5C\x63\x22\x2C\x22\x5C\x75\x5C\x7A\x5C\x64\x5C\x31\x53\x5C\x66\x5C\x31\x71\x5C\x4D\x22\x2C\x22\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x45\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x22\x2C\x22\x5C\x4A\x5C\x4A\x5C\x31\x6C\x5C\x45\x5C\x7A\x5C\x75\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x69\x5C\x75\x5C\x68\x5C\x64\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x5C\x71\x5C\x33\x49\x5C\x32\x72\x5C\x31\x79\x5C\x6A\x5C\x46\x5C\x50\x5C\x64\x5C\x32\x41\x5C\x34\x72\x5C\x70\x5C\x68\x5C\x4A\x5C\x32\x41\x5C\x32\x72\x5C\x31\x47\x5C\x72\x5C\x32\x61\x5C\x31\x42\x5C\x6C\x5C\x4D\x5C\x31\x6A\x5C\x34\x6B\x5C\x32\x62\x5C\x4A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x6A\x5C\x31\x4E\x5C\x69\x5C\x4A\x5C\x33\x4C\x5C\x6C\x5C\x33\x63\x5C\x71\x5C\x63\x5C\x64\x5C\x31\x77\x5C\x70\x5C\x50\x5C\x32\x61\x5C\x31\x4A\x5C\x70\x5C\x33\x4E\x5C\x6A\x5C\x31\x41\x5C\x33\x74\x5C\x31\x46\x5C\x68\x5C\x75\x5C\x31\x7A\x5C\x69\x5C\x31\x59\x5C\x75\x5C\x31\x71\x5C\x32\x47\x5C\x31\x45\x5C\x31\x59\x5C\x32\x62\x5C\x31\x6A\x5C\x37\x4B\x5C\x47\x5C\x31\x4A\x5C\x33\x49\x5C\x31\x77\x5C\x31\x53\x5C\x70\x5C\x33\x78\x5C\x33\x46\x5C\x31\x6A\x5C\x69\x5C\x32\x41\x5C\x33\x77\x5C\x33\x49\x5C\x4A\x5C\x69\x5C\x31\x47\x5C\x31\x45\x5C\x4A\x5C\x66\x5C\x50\x5C\x66\x5C\x64\x5C\x66\x5C\x6C\x5C\x45\x5C\x31\x46\x5C\x75\x5C\x46\x22\x2C\x22\x5C\x4A\x5C\x69\x5C\x31\x47\x5C\x31\x45\x22\x2C\x22\x5C\x4A\x5C\x69\x5C\x31\x47\x5C\x31\x59\x22\x2C\x22\x5C\x4A\x5C\x4A\x5C\x6A\x5C\x47\x5C\x31\x47\x5C\x45\x5C\x46\x5C\x68\x5C\x68\x5C\x46\x5C\x6A\x5C\x63\x5C\x42\x5C\x69\x5C\x63\x5C\x6C\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x5C\x31\x71\x5C\x33\x68\x5C\x79\x5C\x54\x5C\x33\x46\x5C\x31\x5A\x5C\x32\x74\x5C\x32\x74\x5C\x50\x5C\x50\x5C\x31\x4E\x5C\x31\x79\x5C\x55\x5C\x31\x45\x5C\x54\x5C\x33\x77\x5C\x4D\x5C\x33\x74\x5C\x31\x46\x5C\x31\x62\x5C\x34\x6B\x5C\x42\x5C\x31\x5A\x5C\x6A\x5C\x33\x4C\x5C\x50\x5C\x71\x5C\x32\x61\x5C\x31\x59\x5C\x33\x75\x5C\x31\x59\x5C\x32\x47\x5C\x31\x53\x5C\x31\x62\x5C\x33\x63\x5C\x32\x41\x5C\x33\x4C\x5C\x33\x44\x5C\x32\x6A\x5C\x6E\x5C\x7A\x5C\x31\x4E\x5C\x63\x5C\x31\x56\x5C\x33\x4E\x5C\x64\x5C\x31\x46\x5C\x31\x42\x5C\x34\x72\x5C\x33\x44\x5C\x31\x79\x5C\x32\x61\x5C\x33\x4E\x5C\x32\x47\x5C\x31\x45\x5C\x55\x5C\x33\x74\x5C\x47\x5C\x31\x56\x5C\x71\x5C\x31\x42\x5C\x31\x6A\x5C\x4C\x5C\x69\x5C\x31\x47\x5C\x31\x45\x22\x2C\x22\x5C\x4A\x5C\x4A\x5C\x6C\x5C\x63\x5C\x69\x5C\x68\x5C\x42\x5C\x6C\x5C\x70\x5C\x63\x5C\x69\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x5C\x6B\x5C\x72\x5C\x46\x5C\x4A\x5C\x7A\x5C\x6A\x5C\x66\x5C\x6E\x5C\x31\x62\x5C\x45\x5C\x46\x5C\x6B\x5C\x4B\x22\x2C\x22\x5C\x4B\x5C\x6B\x5C\x54\x5C\x63\x5C\x79\x5C\x31\x42\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x22\x2C\x22\x5C\x4B\x5C\x6B\x5C\x54\x5C\x63\x5C\x79\x5C\x31\x4A\x5C\x63\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x47\x5C\x63\x5C\x6B\x5C\x46\x5C\x47\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x47\x5C\x63\x5C\x66\x5C\x79\x5C\x63\x5C\x6C\x5C\x71\x5C\x6B\x5C\x6E\x5C\x6E\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x57\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x5C\x71\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6C\x5C\x41\x5C\x4F\x5C\x41\x5C\x45\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x6B\x5C\x6E\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x64\x5C\x47\x5C\x63\x5C\x6B\x5C\x66\x5C\x31\x42\x5C\x64\x5C\x6B\x5C\x70\x5C\x31\x62\x5C\x4D\x5C\x31\x42\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x22\x2C\x22\x5C\x63\x5C\x66\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x50\x5C\x6B\x5C\x63\x5C\x55\x5C\x31\x6A\x5C\x6A\x5C\x6A\x22\x2C\x22\x5C\x75\x5C\x7A\x5C\x64\x5C\x31\x4A\x5C\x63\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x57\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x5C\x71\x5C\x66\x5C\x70\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x22\x2C\x22\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x22\x2C\x22\x5C\x4B\x5C\x68\x5C\x70\x5C\x42\x5C\x69\x22\x2C\x22\x5C\x6B\x5C\x6E\x5C\x75\x5C\x42\x5C\x64\x22\x2C\x22\x5C\x79\x5C\x6B\x5C\x69\x5C\x75\x5C\x6A\x5C\x66\x5C\x4D\x22\x2C\x22\x5C\x4B\x5C\x6A\x5C\x63\x5C\x54\x22\x2C\x22\x5C\x70\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x4B\x5C\x66\x5C\x79\x5C\x63\x5C\x32\x62\x5C\x6E\x22\x2C\x22\x5C\x70\x5C\x6A\x5C\x6B\x5C\x70\x5C\x31\x62\x22\x2C\x22\x5C\x45\x5C\x69\x5C\x47\x5C\x68\x5C\x55\x5C\x71\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x72\x5C\x68\x5C\x50\x5C\x63\x5C\x31\x77\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x50\x5C\x66\x5C\x6A\x22\x2C\x22\x5C\x7A\x5C\x6A\x5C\x42\x5C\x6C\x22\x2C\x22\x5C\x4B\x5C\x66\x5C\x79\x5C\x63\x5C\x32\x6A\x5C\x42\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x5C\x71\x5C\x70\x5C\x6A\x5C\x68\x5C\x69\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x47\x5C\x66\x5C\x69\x5C\x31\x77\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x68\x5C\x4B\x5C\x4B\x22\x2C\x22\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x66\x5C\x70\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x22\x2C\x22\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x5C\x31\x77\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x45\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x31\x6C\x5C\x71\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x41\x5C\x66\x5C\x45\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x5C\x31\x6B\x5C\x41\x5C\x45\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x41\x5C\x66\x5C\x45\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x57\x22\x2C\x22\x5C\x64\x5C\x63\x5C\x54\x5C\x64\x22\x2C\x22\x5C\x79\x5C\x66\x5C\x64\x5C\x66\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x64\x5C\x63\x5C\x54\x5C\x64\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6E\x5C\x79\x22\x2C\x22\x5C\x45\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x6B\x5C\x70\x5C\x68\x5C\x6E\x5C\x69\x5C\x41\x5C\x66\x22\x2C\x22\x5C\x69\x5C\x47\x5C\x68\x5C\x6C\x5C\x64\x5C\x70\x5C\x68\x5C\x79\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6A\x5C\x70\x5C\x47\x5C\x6B\x5C\x72\x5C\x75\x5C\x71\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6A\x5C\x70\x5C\x47\x5C\x6B\x5C\x72\x5C\x75\x5C\x71\x5C\x64\x5C\x63\x5C\x54\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x31\x4A\x5C\x66\x5C\x6B\x5C\x6A\x5C\x31\x77\x5C\x47\x5C\x6B\x5C\x72\x5C\x75\x5C\x41\x5C\x45\x5C\x55\x5C\x6B\x5C\x79\x5C\x46\x5C\x63\x5C\x64\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x64\x5C\x68\x5C\x31\x53\x5C\x68\x5C\x55\x5C\x63\x5C\x6C\x5C\x31\x77\x5C\x66\x5C\x69\x5C\x63\x22\x2C\x22\x5C\x46\x5C\x63\x5C\x64\x5C\x7A\x5C\x42\x5C\x64\x5C\x64\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x4E\x5C\x63\x5C\x72\x5C\x4F\x5C\x31\x54\x5C\x31\x6C\x5C\x4E\x5C\x4A\x5C\x63\x5C\x72\x5C\x4F\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x66\x5C\x70\x5C\x63\x5C\x31\x7A\x5C\x63\x5C\x54\x5C\x64\x22\x2C\x22\x5C\x34\x4A\x5C\x69\x22\x2C\x22\x5C\x63\x5C\x72\x22\x2C\x22\x5C\x6B\x5C\x70\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x22\x2C\x22\x5C\x69\x5C\x6B\x5C\x31\x71\x5C\x63\x22\x2C\x22\x5C\x6B\x5C\x6E\x5C\x4B\x5C\x68\x22\x2C\x22\x5C\x69\x5C\x64\x5C\x4D\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x7A\x5C\x42\x5C\x64\x5C\x64\x5C\x68\x5C\x6E\x5C\x41\x5C\x7A\x5C\x64\x5C\x6E\x5C\x41\x5C\x54\x5C\x31\x79\x22\x2C\x22\x5C\x7A\x5C\x42\x5C\x64\x5C\x64\x5C\x68\x5C\x6E\x5C\x41\x5C\x7A\x5C\x64\x5C\x6E\x22\x2C\x22\x5C\x70\x5C\x63\x5C\x6E\x5C\x64\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x6B\x5C\x69\x5C\x71\x5C\x70\x22\x2C\x22\x5C\x54\x5C\x31\x79\x5C\x41\x22\x2C\x22\x5C\x54\x5C\x31\x79\x22\x2C\x22\x5C\x4E\x5C\x69\x5C\x75\x5C\x66\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x7A\x5C\x64\x5C\x6E\x5C\x71\x5C\x6B\x5C\x6E\x5C\x4B\x5C\x68\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x7A\x5C\x66\x5C\x70\x5C\x31\x62\x5C\x46\x5C\x6C\x5C\x68\x5C\x42\x5C\x6E\x5C\x79\x5C\x31\x66\x22\x2C\x22\x5C\x31\x65\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x5C\x41\x5C\x66\x22\x2C\x22\x5C\x31\x68\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x70\x5C\x64\x5C\x4B\x5C\x68\x5C\x6C\x5C\x72\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x70\x5C\x64\x5C\x71\x5C\x4B\x5C\x68\x5C\x6C\x5C\x72\x5C\x71\x5C\x55\x5C\x6B\x5C\x79\x5C\x46\x5C\x63\x5C\x64\x5C\x44\x5C\x4A\x5C\x4F\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x66\x5C\x70\x5C\x63\x5C\x34\x78\x5C\x6B\x5C\x64\x5C\x47\x22\x2C\x22\x5C\x57\x5C\x31\x77\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x70\x5C\x64\x5C\x33\x68\x5C\x68\x5C\x6C\x5C\x72\x5C\x31\x6C\x5C\x41\x5C\x45\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x70\x5C\x64\x5C\x71\x5C\x4B\x5C\x68\x5C\x6C\x5C\x72\x5C\x71\x5C\x4B\x5C\x68\x5C\x6C\x5C\x72\x22\x2C\x22\x5C\x57\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x5C\x41\x5C\x45\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x70\x5C\x64\x5C\x71\x5C\x4B\x5C\x68\x5C\x6C\x5C\x72\x5C\x71\x5C\x55\x5C\x6B\x5C\x79\x5C\x46\x5C\x63\x5C\x64\x22\x2C\x22\x5C\x31\x68\x5C\x6A\x5C\x63\x5C\x4B\x5C\x64\x5C\x69\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x5C\x31\x67\x22\x2C\x22\x5C\x6B\x5C\x69\x5C\x71\x5C\x6A\x5C\x63\x5C\x4B\x5C\x64\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x72\x5C\x68\x5C\x50\x5C\x63\x22\x2C\x22\x5C\x31\x68\x5C\x6C\x5C\x6B\x5C\x46\x5C\x47\x5C\x64\x5C\x69\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x5C\x31\x67\x22\x2C\x22\x5C\x6B\x5C\x69\x5C\x71\x5C\x6C\x5C\x6B\x5C\x46\x5C\x47\x5C\x64\x22\x2C\x22\x5C\x31\x68\x5C\x4B\x5C\x42\x5C\x6A\x5C\x6A\x5C\x55\x5C\x6B\x5C\x79\x5C\x64\x5C\x47\x5C\x31\x67\x22\x2C\x22\x5C\x6E\x5C\x68\x5C\x71\x5C\x69\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x5C\x41\x5C\x7A\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x69\x5C\x42\x5C\x70\x5C\x70\x5C\x63\x5C\x69\x5C\x69\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x31\x42\x5C\x42\x5C\x70\x5C\x70\x5C\x63\x5C\x69\x5C\x69\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x72\x5C\x63\x5C\x69\x5C\x69\x5C\x66\x5C\x46\x5C\x63\x5C\x41\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x69\x5C\x42\x5C\x70\x5C\x70\x5C\x63\x5C\x69\x5C\x69\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x6B\x5C\x6E\x5C\x4B\x5C\x68\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x32\x62\x5C\x6E\x5C\x4B\x5C\x68\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x72\x5C\x63\x5C\x69\x5C\x69\x5C\x66\x5C\x46\x5C\x63\x5C\x41\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x6B\x5C\x6E\x5C\x4B\x5C\x68\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x55\x5C\x66\x5C\x6C\x5C\x6E\x5C\x6B\x5C\x6E\x5C\x46\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x34\x78\x5C\x66\x5C\x6C\x5C\x6E\x5C\x6B\x5C\x6E\x5C\x46\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x72\x5C\x63\x5C\x69\x5C\x69\x5C\x66\x5C\x46\x5C\x63\x5C\x41\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x55\x5C\x66\x5C\x6C\x5C\x6E\x5C\x6B\x5C\x6E\x5C\x46\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x63\x5C\x6C\x5C\x6C\x5C\x68\x5C\x6C\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x31\x5A\x5C\x6C\x5C\x6C\x5C\x68\x5C\x6C\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x72\x5C\x63\x5C\x69\x5C\x69\x5C\x66\x5C\x46\x5C\x63\x5C\x41\x5C\x66\x5C\x6A\x5C\x63\x5C\x6C\x5C\x64\x5C\x71\x5C\x63\x5C\x6C\x5C\x6C\x5C\x68\x5C\x6C\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x31\x68\x5C\x70\x5C\x68\x5C\x79\x5C\x63\x5C\x7A\x5C\x68\x5C\x54\x5C\x31\x67\x22\x2C\x22\x5C\x31\x68\x5C\x70\x5C\x68\x5C\x79\x5C\x63\x5C\x33\x78\x5C\x68\x5C\x54\x5C\x31\x67\x22\x2C\x22\x5C\x4E\x5C\x75\x5C\x6C\x5C\x63\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x70\x5C\x68\x5C\x79\x5C\x63\x5C\x71\x5C\x7A\x5C\x68\x5C\x54\x5C\x44\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x4A\x5C\x75\x5C\x6C\x5C\x63\x5C\x4F\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x5C\x41\x5C\x7A\x5C\x6A\x5C\x68\x5C\x70\x5C\x31\x62\x5C\x32\x47\x5C\x42\x5C\x68\x5C\x64\x5C\x63\x22\x2C\x22\x5C\x75\x5C\x6C\x5C\x63\x5C\x50\x5C\x63\x5C\x6E\x5C\x64\x5C\x31\x4E\x5C\x63\x5C\x4B\x5C\x66\x5C\x42\x5C\x6A\x5C\x64\x22\x2C\x22\x5C\x55\x5C\x6B\x5C\x79\x5C\x64\x5C\x47\x22\x2C\x22\x5C\x33\x75\x5C\x7A\x5C\x6A\x5C\x66\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x69\x5C\x70\x5C\x6C\x5C\x68\x5C\x6A\x5C\x6A\x5C\x7A\x5C\x66\x5C\x6C\x5C\x69\x5C\x4C\x5C\x4D\x5C\x63\x5C\x69\x5C\x31\x6B\x5C\x6C\x5C\x63\x5C\x69\x5C\x6B\x5C\x31\x71\x5C\x66\x5C\x7A\x5C\x6A\x5C\x63\x5C\x4C\x5C\x4D\x5C\x63\x5C\x69\x5C\x31\x6B\x5C\x64\x5C\x68\x5C\x68\x5C\x6A\x5C\x7A\x5C\x66\x5C\x6C\x5C\x4C\x5C\x31\x41\x5C\x31\x6B\x5C\x55\x5C\x6B\x5C\x79\x5C\x64\x5C\x47\x5C\x4C\x22\x2C\x22\x5C\x31\x6B\x5C\x47\x5C\x63\x5C\x6B\x5C\x46\x5C\x47\x5C\x64\x5C\x4C\x22\x2C\x22\x5C\x31\x6B\x5C\x64\x5C\x68\x5C\x75\x5C\x4C\x5C\x31\x45\x5C\x31\x41\x5C\x31\x6B\x5C\x6A\x5C\x63\x5C\x4B\x5C\x64\x5C\x4C\x5C\x31\x45\x5C\x31\x41\x22\x2C\x22\x5C\x68\x5C\x75\x5C\x63\x5C\x6E\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x7A\x5C\x64\x5C\x71\x5C\x55\x5C\x6B\x5C\x6E\x5C\x79\x5C\x68\x5C\x55\x22\x2C\x22\x5C\x69\x5C\x47\x5C\x66\x5C\x6C\x5C\x63\x5C\x71\x5C\x66\x5C\x70\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x69\x5C\x47\x5C\x66\x5C\x6C\x5C\x63\x5C\x41\x5C\x45\x5C\x69\x5C\x47\x5C\x68\x5C\x55\x5C\x71\x5C\x72\x5C\x68\x5C\x6C\x5C\x63\x5C\x41\x5C\x45\x5C\x7A\x5C\x64\x5C\x6E\x5C\x31\x6B\x5C\x41\x5C\x45\x5C\x69\x5C\x47\x5C\x66\x5C\x6C\x5C\x63\x5C\x71\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x5C\x31\x6B\x5C\x41\x5C\x45\x5C\x47\x5C\x6B\x5C\x79\x5C\x63\x5C\x71\x5C\x72\x5C\x68\x5C\x79\x5C\x66\x5C\x6A\x5C\x31\x6B\x5C\x41\x5C\x57\x5C\x69\x5C\x47\x5C\x66\x5C\x6C\x5C\x63\x5C\x71\x5C\x68\x5C\x50\x5C\x63\x5C\x6C\x5C\x6A\x5C\x66\x5C\x4D\x22\x2C\x22\x5C\x69\x5C\x63\x5C\x6A\x5C\x63\x5C\x70\x5C\x64\x22\x2C\x22\x5C\x70\x5C\x47\x5C\x6B\x5C\x6A\x5C\x79\x5C\x6C\x5C\x63\x5C\x6E\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x75\x5C\x4D\x22\x2C\x22\x5C\x63\x5C\x54\x5C\x63\x5C\x70\x5C\x31\x77\x5C\x68\x5C\x72\x5C\x72\x5C\x66\x5C\x6E\x5C\x79\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x75\x5C\x6B\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x75\x5C\x6B\x5C\x63\x5C\x79\x5C\x71\x5C\x68\x5C\x4B\x5C\x4B\x22\x2C\x22\x5C\x7A\x5C\x42\x5C\x64\x5C\x64\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x45\x5C\x70\x5C\x68\x5C\x75\x5C\x4D\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x66\x22\x2C\x22\x5C\x4E\x5C\x6A\x5C\x6B\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x22\x2C\x22\x5C\x44\x5C\x4F\x5C\x4E\x5C\x66\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x4B\x5C\x66\x5C\x71\x22\x2C\x22\x5C\x44\x5C\x41\x5C\x6C\x5C\x63\x5C\x6A\x5C\x4C\x5C\x44\x5C\x6E\x5C\x68\x5C\x4B\x5C\x68\x5C\x6A\x5C\x6A\x5C\x68\x5C\x55\x5C\x41\x5C\x6E\x5C\x68\x5C\x68\x5C\x75\x5C\x63\x5C\x6E\x5C\x63\x5C\x6C\x5C\x44\x5C\x41\x5C\x64\x5C\x66\x5C\x6C\x5C\x46\x5C\x63\x5C\x64\x5C\x4C\x5C\x44\x5C\x33\x75\x5C\x7A\x5C\x6A\x5C\x66\x5C\x6E\x5C\x31\x62\x5C\x44\x5C\x4A\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x6A\x5C\x6B\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x42\x5C\x6A\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x5C\x69\x5C\x41\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x41\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x5C\x44\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x42\x5C\x6A\x5C\x4F\x22\x2C\x22\x5C\x45\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x5C\x69\x22\x2C\x22\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6E\x5C\x79\x5C\x31\x7A\x5C\x68\x22\x2C\x22\x5C\x6A\x5C\x6B\x22\x2C\x22\x5C\x45\x5C\x66\x5C\x7A\x5C\x68\x5C\x42\x5C\x64\x5C\x71\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x41\x5C\x45\x5C\x66\x5C\x42\x5C\x64\x5C\x47\x5C\x68\x5C\x6C\x5C\x71\x5C\x64\x5C\x63\x5C\x54\x5C\x64\x22\x2C\x22\x5C\x6C\x5C\x63\x5C\x69\x5C\x42\x5C\x6A\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x6A\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x22\x2C\x22\x5C\x45\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x64\x5C\x66\x5C\x46\x22\x2C\x22\x5C\x45\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x4A\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x22\x2C\x22\x5C\x4A\x5C\x69\x5C\x63\x5C\x66\x5C\x6C\x5C\x70\x5C\x47\x5C\x4A\x5C\x6A\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x5C\x4A\x22\x2C\x22\x5C\x45\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x41\x5C\x45\x5C\x64\x5C\x6B\x5C\x64\x5C\x6A\x5C\x63\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x69\x5C\x70\x5C\x6C\x5C\x68\x5C\x6A\x5C\x6A\x22\x2C\x22\x5C\x64\x5C\x6C\x5C\x6B\x5C\x46\x5C\x46\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x6A\x5C\x68\x5C\x66\x5C\x79\x5C\x41\x5C\x6C\x5C\x63\x5C\x69\x5C\x6B\x5C\x31\x71\x5C\x63\x5C\x41\x5C\x69\x5C\x70\x5C\x6C\x5C\x68\x5C\x6A\x5C\x6A\x22\x2C\x22\x5C\x69\x5C\x70\x5C\x6C\x5C\x68\x5C\x6A\x5C\x6A\x5C\x31\x7A\x5C\x68\x5C\x75\x22\x2C\x22\x5C\x64\x5C\x68\x5C\x75\x22\x2C\x22\x5C\x68\x5C\x4B\x5C\x4B\x5C\x69\x5C\x63\x5C\x64\x22\x2C\x22\x5C\x68\x5C\x4B\x5C\x4B\x22\x2C\x22\x5C\x57\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x57\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x22\x2C\x22\x5C\x57\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x5C\x41\x5C\x45\x5C\x33\x77\x5C\x31\x7A\x5C\x31\x4A\x5C\x31\x53\x22\x2C\x22\x5C\x64\x5C\x4D\x5C\x75\x5C\x63\x22\x2C\x22\x5C\x57\x5C\x64\x5C\x68\x5C\x75\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x6B\x5C\x6E\x5C\x42\x5C\x63\x5C\x41\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x71\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x4D\x22\x2C\x22\x5C\x6B\x5C\x69\x5C\x71\x5C\x47\x5C\x6B\x5C\x79\x5C\x79\x5C\x63\x5C\x6E\x22\x2C\x22\x5C\x47\x5C\x6B\x5C\x79\x5C\x63\x22\x2C\x22\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x5C\x71\x5C\x69\x5C\x4D\x5C\x69\x5C\x64\x5C\x63\x5C\x72\x5C\x71\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x46\x5C\x63\x5C\x6C\x5C\x41\x5C\x6B\x5C\x69\x5C\x71\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x7A\x5C\x64\x5C\x6E\x22\x2C\x22\x5C\x45\x5C\x66\x5C\x50\x5C\x66\x5C\x64\x5C\x66\x5C\x6C\x5C\x71\x5C\x6B\x5C\x72\x5C\x66\x5C\x46\x5C\x63\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x66\x5C\x6B\x5C\x6E\x5C\x63\x5C\x6C\x5C\x41\x5C\x6B\x5C\x72\x5C\x46\x22\x2C\x22\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x5C\x41\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x71\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x4D\x22\x2C\x22\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x5C\x41\x5C\x57\x5C\x64\x5C\x68\x5C\x75\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x6B\x5C\x6E\x5C\x42\x5C\x63\x22\x2C\x22\x5C\x57\x5C\x64\x5C\x68\x5C\x75\x5C\x71\x5C\x70\x5C\x63\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x71\x5C\x6C\x5C\x63\x5C\x75\x5C\x6A\x5C\x4D\x5C\x7A\x5C\x68\x5C\x54\x5C\x71\x5C\x64\x5C\x47\x5C\x6C\x5C\x63\x5C\x66\x5C\x79\x22\x2C\x22\x5C\x69\x5C\x47\x5C\x68\x5C\x55\x22\x2C\x22\x5C\x45\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x71\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x6B\x5C\x64\x5C\x4D\x5C\x31\x66\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6A\x5C\x63\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x68\x5C\x75\x5C\x66\x5C\x70\x5C\x6B\x5C\x64\x5C\x4D\x5C\x31\x66\x5C\x31\x6C\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x75\x5C\x68\x5C\x69\x5C\x6B\x5C\x64\x5C\x6B\x5C\x68\x5C\x6E\x5C\x31\x66\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x31\x71\x5C\x71\x5C\x6B\x5C\x6E\x5C\x79\x5C\x63\x5C\x54\x5C\x31\x66\x5C\x31\x6C\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x4B\x5C\x68\x5C\x6E\x5C\x64\x5C\x71\x5C\x69\x5C\x6B\x5C\x31\x71\x5C\x63\x5C\x31\x66\x5C\x31\x6C\x5C\x34\x47\x5C\x75\x5C\x54\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x5C\x31\x66\x5C\x50\x5C\x66\x5C\x6C\x5C\x34\x48\x5C\x71\x5C\x71\x5C\x4B\x5C\x68\x5C\x68\x5C\x64\x5C\x63\x5C\x6C\x5C\x7A\x5C\x66\x5C\x6C\x5C\x71\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x5C\x34\x49\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x72\x5C\x66\x5C\x6C\x5C\x46\x5C\x6B\x5C\x6E\x5C\x31\x66\x5C\x31\x41\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x22\x2C\x22\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x6B\x5C\x64\x5C\x4D\x5C\x31\x66\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6A\x5C\x63\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x68\x5C\x75\x5C\x66\x5C\x70\x5C\x6B\x5C\x64\x5C\x4D\x5C\x31\x66\x5C\x31\x6C\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x75\x5C\x68\x5C\x69\x5C\x6B\x5C\x64\x5C\x6B\x5C\x68\x5C\x6E\x5C\x31\x66\x5C\x6C\x5C\x63\x5C\x6A\x5C\x66\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x31\x71\x5C\x71\x5C\x6B\x5C\x6E\x5C\x79\x5C\x63\x5C\x54\x5C\x31\x66\x5C\x31\x6C\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x4B\x5C\x68\x5C\x6E\x5C\x64\x5C\x71\x5C\x69\x5C\x6B\x5C\x31\x71\x5C\x63\x5C\x31\x66\x5C\x31\x6C\x5C\x34\x47\x5C\x75\x5C\x54\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x5C\x31\x66\x5C\x50\x5C\x66\x5C\x6C\x5C\x34\x48\x5C\x71\x5C\x71\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x70\x5C\x68\x5C\x6A\x5C\x68\x5C\x6C\x5C\x34\x49\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x5C\x72\x5C\x66\x5C\x6C\x5C\x46\x5C\x6B\x5C\x6E\x5C\x31\x66\x5C\x31\x41\x5C\x31\x6E\x5C\x6B\x5C\x72\x5C\x75\x5C\x68\x5C\x6C\x5C\x64\x5C\x66\x5C\x6E\x5C\x64\x5C\x31\x65\x22\x2C\x22\x5C\x33\x78\x5C\x6A\x5C\x68\x5C\x46\x5C\x46\x5C\x63\x5C\x6C\x5C\x41\x5C\x31\x7A\x5C\x63\x5C\x72\x5C\x75\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x69\x22\x2C\x22\x5C\x47\x5C\x64\x5C\x64\x5C\x75\x5C\x69\x5C\x31\x66\x5C\x4A\x5C\x4A\x5C\x75\x5C\x6C\x5C\x68\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x46\x5C\x63\x5C\x6C\x5C\x64\x5C\x63\x5C\x72\x5C\x75\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x69\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x22\x2C\x22\x5C\x66\x5C\x57\x5C\x75\x5C\x6C\x5C\x68\x5C\x7A\x5C\x64\x5C\x63\x5C\x72\x5C\x75\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x69\x22\x2C\x22\x5C\x6A\x5C\x68\x5C\x70\x5C\x66\x5C\x64\x5C\x6B\x5C\x68\x5C\x6E\x22\x2C\x22\x5C\x66\x5C\x57\x5C\x75\x5C\x6C\x5C\x68\x5C\x7A\x5C\x64\x5C\x63\x5C\x72\x5C\x75\x5C\x6A\x5C\x66\x5C\x64\x5C\x63\x5C\x69\x5C\x31\x66\x5C\x50\x5C\x6B\x5C\x69\x5C\x6B\x5C\x7A\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x7A\x5C\x64\x5C\x71\x5C\x6A\x5C\x66\x5C\x31\x71\x5C\x4D\x22\x2C\x22\x5C\x6E\x5C\x68\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x5C\x41\x5C\x45\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x5C\x31\x6B\x5C\x45\x5C\x63\x5C\x6E\x5C\x64\x5C\x6C\x5C\x4D\x5C\x71\x5C\x66\x5C\x50\x5C\x66\x5C\x64\x5C\x66\x5C\x6C\x5C\x41\x5C\x45\x5C\x66\x5C\x50\x5C\x66\x5C\x64\x5C\x66\x5C\x6C\x22\x2C\x22\x5C\x70\x5C\x6A\x5C\x68\x5C\x6E\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x6A\x5C\x68\x5C\x46\x5C\x68\x5C\x41\x5C\x66\x22\x2C\x22\x5C\x47\x5C\x31\x6C\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x6A\x5C\x68\x5C\x46\x5C\x68\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x6E\x5C\x66\x5C\x50\x22\x2C\x22\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x6E\x5C\x66\x5C\x50\x22\x2C\x22\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x22\x2C\x22\x5C\x4E\x5C\x7A\x5C\x42\x5C\x64\x5C\x64\x5C\x68\x5C\x6E\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x69\x5C\x42\x5C\x7A\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x71\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x5C\x41\x5C\x7A\x5C\x64\x5C\x6E\x5C\x44\x5C\x41\x5C\x66\x5C\x6C\x5C\x6B\x5C\x66\x5C\x71\x5C\x6A\x5C\x66\x5C\x7A\x5C\x63\x5C\x6A\x5C\x4C\x5C\x44\x5C\x63\x5C\x54\x5C\x75\x5C\x66\x5C\x6E\x5C\x79\x5C\x44\x5C\x4A\x5C\x4F\x22\x2C\x22\x5C\x66\x5C\x4B\x5C\x64\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x45\x5C\x47\x5C\x66\x5C\x69\x5C\x71\x5C\x69\x5C\x42\x5C\x7A\x5C\x41\x5C\x4F\x5C\x41\x5C\x66\x22\x2C\x22\x5C\x6E\x5C\x66\x5C\x50\x5C\x71\x5C\x66\x5C\x70\x5C\x64\x5C\x6B\x5C\x50\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x71\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x5C\x31\x6B\x5C\x41\x5C\x45\x5C\x47\x5C\x6B\x5C\x79\x5C\x63\x5C\x71\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x31\x6B\x5C\x41\x5C\x57\x5C\x68\x5C\x50\x5C\x63\x5C\x6C\x5C\x6A\x5C\x66\x5C\x4D\x22\x2C\x22\x5C\x63\x5C\x54\x5C\x75\x5C\x66\x5C\x6E\x5C\x79\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x69\x5C\x6A\x5C\x6B\x5C\x79\x5C\x63\x5C\x31\x7A\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x45\x5C\x69\x5C\x42\x5C\x7A\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x41\x5C\x45\x5C\x69\x5C\x42\x5C\x7A\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x71\x5C\x64\x5C\x68\x5C\x46\x5C\x46\x5C\x6A\x5C\x63\x22\x2C\x22\x5C\x57\x5C\x72\x5C\x68\x5C\x7A\x5C\x6B\x5C\x6A\x5C\x63\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x22\x2C\x22\x5C\x57\x5C\x47\x5C\x63\x5C\x66\x5C\x79\x5C\x63\x5C\x6C\x5C\x7A\x5C\x66\x5C\x6C\x5C\x41\x5C\x45\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x6B\x5C\x70\x5C\x68\x5C\x6E\x5C\x69\x22\x2C\x22\x5C\x57\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x66\x5C\x7A\x5C\x68\x5C\x42\x5C\x64\x5C\x71\x5C\x69\x5C\x63\x5C\x70\x5C\x64\x5C\x6B\x5C\x68\x5C\x6E\x5C\x41\x5C\x45\x5C\x69\x5C\x68\x5C\x70\x5C\x6B\x5C\x66\x5C\x6A\x5C\x71\x5C\x6B\x5C\x70\x5C\x68\x5C\x6E\x5C\x69\x22\x2C\x22\x5C\x57\x5C\x4B\x5C\x68\x5C\x68\x5C\x64\x5C\x63\x5C\x6C\x5C\x71\x5C\x72\x5C\x63\x5C\x6E\x5C\x42\x5C\x41\x5C\x45\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x5C\x71\x5C\x6A\x5C\x6B\x5C\x69\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x64\x5C\x63\x5C\x54\x5C\x64\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x72\x5C\x71\x5C\x4B\x5C\x68\x5C\x68\x5C\x64\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x45\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x47\x5C\x63\x5C\x66\x5C\x79\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x6B\x5C\x69\x5C\x71\x5C\x4B\x5C\x6B\x5C\x54\x5C\x63\x5C\x79\x22\x2C\x22\x5C\x57\x5C\x72\x5C\x66\x5C\x6B\x5C\x6E\x5C\x71\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6C\x5C\x31\x6B\x5C\x41\x5C\x57\x5C\x69\x5C\x6B\x5C\x79\x5C\x63\x5C\x7A\x5C\x66\x5C\x6C\x5C\x71\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x55\x5C\x55\x5C\x55\x5C\x45\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x71\x5C\x50\x5C\x6B\x5C\x79\x5C\x63\x5C\x68\x5C\x44\x5C\x4A\x5C\x4F\x22\x2C\x22\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x22\x2C\x22\x5C\x57\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x71\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x5C\x41\x5C\x6B\x5C\x4B\x5C\x6C\x5C\x66\x5C\x72\x5C\x63\x22\x2C\x22\x5C\x4E\x5C\x6B\x5C\x72\x5C\x46\x5C\x41\x5C\x69\x5C\x6C\x5C\x70\x5C\x4C\x5C\x44\x5C\x31\x54\x5C\x31\x6C\x5C\x44\x5C\x4A\x5C\x4F\x22\x2C\x22\x5C\x4E\x5C\x79\x5C\x6B\x5C\x50\x5C\x41\x5C\x70\x5C\x6A\x5C\x66\x5C\x69\x5C\x69\x5C\x4C\x5C\x44\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x71\x5C\x50\x5C\x6B\x5C\x79\x5C\x63\x5C\x68\x5C\x44\x5C\x4F\x5C\x4E\x5C\x6B\x5C\x4B\x5C\x6C\x5C\x66\x5C\x72\x5C\x63\x5C\x41\x5C\x6B\x5C\x79\x5C\x4C\x5C\x44\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x44\x5C\x41\x5C\x55\x5C\x6B\x5C\x79\x5C\x64\x5C\x47\x5C\x4C\x5C\x44\x5C\x31\x6C\x5C\x31\x41\x5C\x31\x41\x5C\x34\x4A\x5C\x44\x5C\x41\x5C\x47\x5C\x63\x5C\x6B\x5C\x46\x5C\x47\x5C\x64\x5C\x4C\x5C\x44\x5C\x31\x47\x5C\x31\x45\x5C\x33\x44\x5C\x44\x5C\x41\x5C\x69\x5C\x6C\x5C\x70\x5C\x4C\x5C\x44\x5C\x47\x5C\x64\x5C\x64\x5C\x75\x5C\x69\x5C\x31\x66\x5C\x4A\x5C\x4A\x5C\x55\x5C\x55\x5C\x55\x5C\x45\x5C\x4D\x5C\x68\x5C\x42\x5C\x64\x5C\x42\x5C\x7A\x5C\x63\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x4A\x5C\x63\x5C\x72\x5C\x7A\x5C\x63\x5C\x79\x5C\x4A\x5C\x31\x54\x5C\x31\x6C\x5C\x44\x5C\x41\x5C\x4B\x5C\x6C\x5C\x66\x5C\x72\x5C\x63\x5C\x7A\x5C\x68\x5C\x6C\x5C\x79\x5C\x63\x5C\x6C\x5C\x4C\x5C\x44\x5C\x31\x41\x5C\x44\x5C\x41\x5C\x66\x5C\x6A\x5C\x6A\x5C\x68\x5C\x55\x5C\x4C\x5C\x44\x5C\x66\x5C\x70\x5C\x70\x5C\x63\x5C\x6A\x5C\x63\x5C\x6C\x5C\x68\x5C\x72\x5C\x63\x5C\x64\x5C\x63\x5C\x6C\x5C\x31\x65\x5C\x41\x5C\x66\x5C\x42\x5C\x64\x5C\x68\x5C\x75\x5C\x6A\x5C\x66\x5C\x4D\x5C\x31\x65\x5C\x41\x5C\x63\x5C\x6E\x5C\x70\x5C\x6C\x5C\x4D\x5C\x75\x5C\x64\x5C\x63\x5C\x79\x5C\x71\x5C\x72\x5C\x63\x5C\x79\x5C\x6B\x5C\x66\x5C\x31\x65\x5C\x41\x5C\x46\x5C\x4D\x5C\x6C\x5C\x68\x5C\x69\x5C\x70\x5C\x68\x5C\x75\x5C\x63\x5C\x31\x65\x5C\x41\x5C\x75\x5C\x6B\x5C\x70\x5C\x64\x5C\x42\x5C\x6C\x5C\x63\x5C\x71\x5C\x6B\x5C\x6E\x5C\x71\x5C\x75\x5C\x6B\x5C\x70\x5C\x64\x5C\x42\x5C\x6C\x5C\x63\x5C\x44\x5C\x41\x5C\x66\x5C\x6A\x5C\x6A\x5C\x68\x5C\x55\x5C\x4B\x5C\x42\x5C\x6A\x5C\x6A\x5C\x69\x5C\x70\x5C\x6C\x5C\x63\x5C\x63\x5C\x6E\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x6B\x5C\x4B\x5C\x6C\x5C\x66\x5C\x72\x5C\x63\x5C\x4F\x5C\x4E\x5C\x4A\x5C\x79\x5C\x6B\x5C\x50\x5C\x4F\x22\x2C\x22\x5C\x75\x5C\x45\x5C\x70\x5C\x68\x5C\x72\x5C\x72\x5C\x63\x5C\x6E\x5C\x64\x5C\x71\x5C\x70\x5C\x68\x5C\x6E\x5C\x64\x5C\x63\x5C\x6E\x5C\x64\x22\x2C\x22\x5C\x6A\x5C\x68\x5C\x66\x5C\x79\x22\x2C\x22\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x71\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x22\x2C\x22\x5C\x4B\x5C\x66\x5C\x79\x5C\x63\x5C\x32\x62\x5C\x6E\x5C\x32\x61\x5C\x75\x22\x2C\x22\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x22\x2C\x22\x5C\x57\x5C\x54\x5C\x79\x5C\x4B\x5C\x70\x5C\x7A\x5C\x71\x5C\x6A\x5C\x68\x5C\x66\x5C\x79\x5C\x71\x5C\x72\x5C\x68\x5C\x6C\x5C\x63\x5C\x71\x5C\x6A\x5C\x6B\x5C\x6E\x5C\x31\x62\x22\x2C\x22\x5C\x57\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x71\x5C\x75\x5C\x66\x5C\x46\x5C\x63\x5C\x6C\x5C\x41\x5C\x45\x5C\x6E\x5C\x68\x5C\x71\x5C\x72\x5C\x68\x5C\x6C\x5C\x63\x22\x2C\x22\x5C\x57\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x71\x5C\x75\x5C\x66\x5C\x46\x5C\x63\x5C\x6C\x5C\x41\x5C\x45\x5C\x6A\x5C\x68\x5C\x66\x5C\x79\x5C\x6B\x5C\x6E\x5C\x46\x22\x2C\x22\x5C\x45\x5C\x7A\x5C\x6A\x5C\x68\x5C\x46\x5C\x71\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x69\x5C\x41\x5C\x45\x5C\x75\x5C\x68\x5C\x69\x5C\x64\x5C\x41\x5C\x45\x5C\x64\x5C\x47\x5C\x42\x5C\x72\x5C\x7A\x5C\x6E\x5C\x66\x5C\x6B\x5C\x6A\x22\x2C\x22\x5C\x57\x5C\x4B\x5C\x68\x5C\x68\x5C\x64\x5C\x63\x5C\x6C\x5C\x71\x5C\x55\x5C\x6C\x5C\x66\x5C\x75\x5C\x75\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x68\x5C\x6E\x5C\x71\x5C\x4B\x5C\x68\x5C\x68\x5C\x64\x5C\x63\x5C\x6C\x22\x2C\x22\x5C\x66\x5C\x6E\x5C\x6B\x5C\x72\x5C\x66\x5C\x64\x5C\x63\x22\x2C\x22\x5C\x47\x5C\x64\x5C\x72\x5C\x6A\x5C\x31\x6B\x5C\x41\x5C\x7A\x5C\x68\x5C\x79\x5C\x4D\x22\x2C\x22\x5C\x57\x5C\x7A\x5C\x66\x5C\x70\x5C\x31\x62\x5C\x71\x5C\x64\x5C\x68\x5C\x75\x22\x5D\x3B\x51\x20\x61\x24\x62\x3D\x5B\x61\x24\x65\x5B\x30\x5D\x2C\x61\x24\x65\x5B\x31\x5D\x2C\x61\x24\x65\x5B\x32\x5D\x2C\x61\x24\x65\x5B\x33\x5D\x2C\x61\x24\x65\x5B\x34\x5D\x2C\x61\x24\x65\x5B\x35\x5D\x2C\x61\x24\x65\x5B\x36\x5D\x2C\x61\x24\x65\x5B\x37\x5D\x2C\x61\x24\x65\x5B\x38\x5D\x2C\x61\x24\x65\x5B\x39\x5D\x2C\x61\x24\x65\x5B\x31\x30\x5D\x2C\x61\x24\x65\x5B\x31\x31\x5D\x2C\x61\x24\x65\x5B\x31\x32\x5D\x2C\x61\x24\x65\x5B\x31\x33\x5D\x2C\x61\x24\x65\x5B\x31\x34\x5D\x2C\x61\x24\x65\x5B\x31\x35\x5D\x2C\x61\x24\x65\x5B\x31\x36\x5D\x2C\x61\x24\x65\x5B\x31\x37\x5D\x2C\x61\x24\x65\x5B\x31\x38\x5D\x2C\x61\x24\x65\x5B\x31\x39\x5D\x2C\x61\x24\x65\x5B\x32\x30\x5D\x2C\x61\x24\x65\x5B\x32\x31\x5D\x2C\x61\x24\x65\x5B\x32\x32\x5D\x2C\x61\x24\x65\x5B\x32\x33\x5D\x2C\x61\x24\x65\x5B\x32\x34\x5D\x2C\x61\x24\x65\x5B\x32\x35\x5D\x2C\x61\x24\x65\x5B\x32\x36\x5D\x2C\x61\x24\x65\x5B\x32\x37\x5D\x2C\x61\x24\x65\x5B\x32\x38\x5D\x2C\x61\x24\x65\x5B\x32\x39\x5D\x2C\x61\x24\x65\x5B\x33\x30\x5D\x2C\x61\x24\x65\x5B\x33\x31\x5D\x2C\x61\x24\x65\x5B\x33\x32\x5D\x2C\x61\x24\x65\x5B\x33\x33\x5D\x2C\x61\x24\x65\x5B\x33\x34\x5D\x2C\x61\x24\x65\x5B\x33\x35\x5D\x2C\x61\x24\x65\x5B\x33\x36\x5D\x2C\x61\x24\x65\x5B\x33\x37\x5D\x2C\x61\x24\x65\x5B\x33\x38\x5D\x2C\x61\x24\x65\x5B\x33\x39\x5D\x2C\x61\x24\x65\x5B\x34\x30\x5D\x2C\x61\x24\x65\x5B\x34\x31\x5D\x2C\x61\x24\x65\x5B\x34\x32\x5D\x2C\x61\x24\x65\x5B\x34\x33\x5D\x2C\x61\x24\x65\x5B\x34\x34\x5D\x2C\x61\x24\x65\x5B\x34\x35\x5D\x2C\x61\x24\x65\x5B\x34\x36\x5D\x2C\x61\x24\x65\x5B\x34\x37\x5D\x2C\x61\x24\x65\x5B\x34\x38\x5D\x2C\x61\x24\x65\x5B\x34\x39\x5D\x2C\x61\x24\x65\x5B\x35\x30\x5D\x2C\x61\x24\x65\x5B\x35\x31\x5D\x2C\x61\x24\x65\x5B\x35\x32\x5D\x2C\x61\x24\x65\x5B\x35\x33\x5D\x2C\x61\x24\x65\x5B\x35\x34\x5D\x2C\x61\x24\x65\x5B\x35\x35\x5D\x2C\x61\x24\x65\x5B\x35\x36\x5D\x2C\x61\x24\x65\x5B\x35\x37\x5D\x2C\x61\x24\x65\x5B\x35\x38\x5D\x2C\x61\x24\x65\x5B\x35\x39\x5D\x2C\x61\x24\x65\x5B\x36\x30\x5D\x2C\x61\x24\x65\x5B\x36\x31\x5D\x2C\x61\x24\x65\x5B\x36\x32\x5D\x2C\x61\x24\x65\x5B\x36\x33\x5D\x2C\x61\x24\x65\x5B\x36\x34\x5D\x2C\x61\x24\x65\x5B\x36\x35\x5D\x2C\x61\x24\x65\x5B\x36\x36\x5D\x2C\x61\x24\x65\x5B\x36\x37\x5D\x2C\x61\x24\x65\x5B\x36\x38\x5D\x2C\x61\x24\x65\x5B\x36\x39\x5D\x2C\x61\x24\x65\x5B\x37\x30\x5D\x2C\x61\x24\x65\x5B\x37\x31\x5D\x2C\x61\x24\x65\x5B\x37\x32\x5D\x2C\x61\x24\x65\x5B\x37\x33\x5D\x2C\x61\x24\x65\x5B\x37\x34\x5D\x2C\x61\x24\x65\x5B\x37\x35\x5D\x2C\x61\x24\x65\x5B\x37\x36\x5D\x2C\x61\x24\x65\x5B\x37\x37\x5D\x2C\x61\x24\x65\x5B\x37\x38\x5D\x2C\x61\x24\x65\x5B\x37\x39\x5D\x2C\x61\x24\x65\x5B\x38\x30\x5D\x2C\x61\x24\x65\x5B\x38\x31\x5D\x2C\x61\x24\x65\x5B\x38\x32\x5D\x2C\x61\x24\x65\x5B\x38\x33\x5D\x2C\x61\x24\x65\x5B\x38\x34\x5D\x2C\x61\x24\x65\x5B\x38\x35\x5D\x2C\x61\x24\x65\x5B\x38\x36\x5D\x2C\x61\x24\x65\x5B\x34\x44\x5D\x2C\x61\x24\x65\x5B\x34\x42\x5D\x2C\x61\x24\x65\x5B\x34\x74\x5D\x2C\x61\x24\x65\x5B\x34\x4C\x5D\x2C\x61\x24\x65\x5B\x34\x57\x5D\x2C\x61\x24\x65\x5B\x35\x64\x5D\x2C\x61\x24\x65\x5B\x32\x52\x5D\x2C\x61\x24\x65\x5B\x35\x63\x5D\x2C\x61\x24\x65\x5B\x35\x62\x5D\x2C\x61\x24\x65\x5B\x32\x4F\x5D\x2C\x61\x24\x65\x5B\x35\x61\x5D\x2C\x61\x24\x65\x5B\x34\x59\x5D\x2C\x61\x24\x65\x5B\x31\x50\x5D\x2C\x61\x24\x65\x5B\x33\x66\x5D\x2C\x61\x24\x65\x5B\x32\x59\x5D\x2C\x61\x24\x65\x5B\x32\x58\x5D\x2C\x61\x24\x65\x5B\x32\x46\x5D\x2C\x61\x24\x65\x5B\x34\x58\x5D\x2C\x61\x24\x65\x5B\x34\x52\x5D\x2C\x61\x24\x65\x5B\x59\x5D\x2C\x61\x24\x65\x5B\x31\x78\x5D\x2C\x61\x24\x65\x5B\x34\x51\x5D\x2C\x61\x24\x65\x5B\x32\x56\x5D\x2C\x61\x24\x65\x5B\x33\x61\x5D\x2C\x61\x24\x65\x5B\x34\x4D\x5D\x2C\x61\x24\x65\x5B\x32\x77\x5D\x2C\x61\x24\x65\x5B\x33\x52\x5D\x2C\x61\x24\x65\x5B\x33\x55\x5D\x2C\x61\x24\x65\x5B\x33\x4F\x5D\x2C\x61\x24\x65\x5B\x33\x50\x5D\x2C\x61\x24\x65\x5B\x33\x51\x5D\x2C\x61\x24\x65\x5B\x33\x54\x5D\x2C\x61\x24\x65\x5B\x33\x56\x5D\x2C\x61\x24\x65\x5B\x33\x47\x5D\x2C\x61\x24\x65\x5B\x32\x65\x5D\x2C\x61\x24\x65\x5B\x33\x45\x5D\x2C\x61\x24\x65\x5B\x33\x59\x5D\x2C\x61\x24\x65\x5B\x33\x57\x5D\x2C\x61\x24\x65\x5B\x5A\x5D\x2C\x61\x24\x65\x5B\x34\x69\x5D\x2C\x61\x24\x65\x5B\x34\x6F\x5D\x2C\x61\x24\x65\x5B\x34\x70\x5D\x2C\x61\x24\x65\x5B\x32\x4C\x5D\x2C\x61\x24\x65\x5B\x31\x43\x5D\x2C\x61\x24\x65\x5B\x32\x51\x5D\x2C\x61\x24\x65\x5B\x32\x43\x5D\x2C\x61\x24\x65\x5B\x34\x6A\x5D\x2C\x61\x24\x65\x5B\x34\x68\x5D\x2C\x61\x24\x65\x5B\x34\x71\x5D\x2C\x61\x24\x65\x5B\x34\x6C\x5D\x2C\x61\x24\x65\x5B\x31\x6D\x5D\x2C\x61\x24\x65\x5B\x34\x6D\x5D\x2C\x61\x24\x65\x5B\x31\x6F\x5D\x2C\x61\x24\x65\x5B\x34\x65\x5D\x2C\x61\x24\x65\x5B\x34\x66\x5D\x2C\x61\x24\x65\x5B\x34\x67\x5D\x2C\x61\x24\x65\x5B\x33\x5A\x5D\x2C\x61\x24\x65\x5B\x34\x6E\x5D\x2C\x61\x24\x65\x5B\x32\x73\x5D\x2C\x61\x24\x65\x5B\x33\x41\x5D\x2C\x61\x24\x65\x5B\x32\x4B\x5D\x2C\x61\x24\x65\x5B\x34\x63\x5D\x2C\x61\x24\x65\x5B\x32\x70\x5D\x2C\x61\x24\x65\x5B\x34\x64\x5D\x2C\x61\x24\x65\x5B\x34\x62\x5D\x2C\x61\x24\x65\x5B\x35\x65\x5D\x2C\x61\x24\x65\x5B\x31\x74\x5D\x2C\x61\x24\x65\x5B\x31\x70\x5D\x2C\x61\x24\x65\x5B\x33\x58\x5D\x2C\x61\x24\x65\x5B\x31\x49\x5D\x2C\x61\x24\x65\x5B\x34\x61\x5D\x2C\x61\x24\x65\x5B\x32\x42\x5D\x2C\x61\x24\x65\x5B\x36\x4F\x5D\x2C\x61\x24\x65\x5B\x36\x50\x5D\x2C\x61\x24\x65\x5B\x35\x67\x5D\x2C\x61\x24\x65\x5B\x32\x78\x5D\x2C\x61\x24\x65\x5B\x36\x52\x5D\x2C\x61\x24\x65\x5B\x36\x53\x5D\x2C\x61\x24\x65\x5B\x32\x68\x5D\x2C\x61\x24\x65\x5B\x32\x76\x5D\x2C\x61\x24\x65\x5B\x36\x54\x5D\x2C\x61\x24\x65\x5B\x35\x66\x5D\x2C\x61\x24\x65\x5B\x32\x4E\x5D\x2C\x61\x24\x65\x5B\x31\x4B\x5D\x2C\x61\x24\x65\x5B\x36\x55\x5D\x2C\x61\x24\x65\x5B\x31\x55\x5D\x2C\x61\x24\x65\x5B\x36\x57\x5D\x2C\x61\x24\x65\x5B\x36\x58\x5D\x2C\x61\x24\x65\x5B\x36\x59\x5D\x2C\x61\x24\x65\x5B\x36\x5A\x5D\x2C\x61\x24\x65\x5B\x37\x61\x5D\x2C\x61\x24\x65\x5B\x37\x62\x5D\x2C\x61\x24\x65\x5B\x36\x56\x5D\x2C\x61\x24\x65\x5B\x36\x4C\x5D\x2C\x61\x24\x65\x5B\x36\x77\x5D\x2C\x61\x24\x65\x5B\x36\x51\x5D\x2C\x61\x24\x65\x5B\x36\x4A\x5D\x2C\x61\x24\x65\x5B\x36\x49\x5D\x2C\x61\x24\x65\x5B\x31\x48\x5D\x2C\x61\x24\x65\x5B\x36\x47\x5D\x2C\x61\x24\x65\x5B\x36\x48\x5D\x2C\x61\x24\x65\x5B\x36\x42\x5D\x2C\x61\x24\x65\x5B\x32\x50\x5D\x2C\x61\x24\x65\x5B\x31\x4D\x5D\x2C\x61\x24\x65\x5B\x36\x41\x5D\x2C\x61\x24\x65\x5B\x36\x7A\x5D\x2C\x61\x24\x65\x5B\x36\x79\x5D\x2C\x61\x24\x65\x5B\x37\x64\x5D\x2C\x61\x24\x65\x5B\x36\x4B\x5D\x2C\x61\x24\x65\x5B\x36\x4D\x5D\x2C\x61\x24\x65\x5B\x37\x65\x5D\x2C\x61\x24\x65\x5B\x37\x6E\x5D\x2C\x61\x24\x65\x5B\x37\x44\x5D\x2C\x61\x24\x65\x5B\x37\x42\x5D\x2C\x61\x24\x65\x5B\x37\x79\x5D\x2C\x61\x24\x65\x5B\x37\x78\x5D\x2C\x61\x24\x65\x5B\x37\x77\x5D\x2C\x61\x24\x65\x5B\x37\x76\x5D\x2C\x61\x24\x65\x5B\x37\x75\x5D\x2C\x61\x24\x65\x5B\x37\x74\x5D\x2C\x61\x24\x65\x5B\x37\x72\x5D\x2C\x61\x24\x65\x5B\x37\x6D\x5D\x2C\x61\x24\x65\x5B\x37\x6A\x5D\x2C\x61\x24\x65\x5B\x37\x68\x5D\x2C\x61\x24\x65\x5B\x37\x67\x5D\x2C\x61\x24\x65\x5B\x37\x63\x5D\x2C\x61\x24\x65\x5B\x31\x4F\x5D\x2C\x61\x24\x65\x5B\x37\x73\x5D\x2C\x61\x24\x65\x5B\x37\x6F\x5D\x2C\x61\x24\x65\x5B\x37\x70\x5D\x2C\x61\x24\x65\x5B\x37\x66\x5D\x2C\x61\x24\x65\x5B\x37\x7A\x5D\x2C\x61\x24\x65\x5B\x37\x6C\x5D\x2C\x61\x24\x65\x5B\x37\x45\x5D\x2C\x61\x24\x65\x5B\x35\x4E\x5D\x2C\x61\x24\x65\x5B\x36\x76\x5D\x2C\x61\x24\x65\x5B\x32\x57\x5D\x2C\x61\x24\x65\x5B\x32\x64\x5D\x2C\x61\x24\x65\x5B\x35\x4A\x5D\x2C\x61\x24\x65\x5B\x35\x4B\x5D\x2C\x61\x24\x65\x5B\x32\x55\x5D\x2C\x61\x24\x65\x5B\x32\x53\x5D\x2C\x61\x24\x65\x5B\x36\x75\x5D\x2C\x61\x24\x65\x5B\x36\x74\x5D\x2C\x61\x24\x65\x5B\x35\x47\x5D\x2C\x61\x24\x65\x5B\x35\x46\x5D\x2C\x61\x24\x65\x5B\x35\x45\x5D\x2C\x61\x24\x65\x5B\x35\x44\x5D\x2C\x61\x24\x65\x5B\x35\x43\x5D\x2C\x61\x24\x65\x5B\x35\x41\x5D\x2C\x61\x24\x65\x5B\x32\x6F\x5D\x2C\x61\x24\x65\x5B\x35\x42\x5D\x2C\x61\x24\x65\x5B\x35\x48\x5D\x2C\x61\x24\x65\x5B\x35\x79\x5D\x2C\x61\x24\x65\x5B\x32\x4A\x5D\x2C\x61\x24\x65\x5B\x35\x72\x5D\x2C\x61\x24\x65\x5B\x35\x71\x5D\x2C\x61\x24\x65\x5B\x35\x50\x5D\x2C\x61\x24\x65\x5B\x35\x51\x5D\x2C\x61\x24\x65\x5B\x35\x52\x5D\x2C\x61\x24\x65\x5B\x32\x75\x5D\x2C\x61\x24\x65\x5B\x35\x56\x5D\x2C\x61\x24\x65\x5B\x32\x49\x5D\x2C\x61\x24\x65\x5B\x32\x67\x5D\x2C\x61\x24\x65\x5B\x31\x52\x5D\x2C\x61\x24\x65\x5B\x31\x4C\x5D\x2C\x61\x24\x65\x5B\x35\x53\x5D\x2C\x61\x24\x65\x5B\x35\x55\x5D\x2C\x61\x24\x65\x5B\x33\x6A\x5D\x2C\x61\x24\x65\x5B\x35\x78\x5D\x2C\x61\x24\x65\x5B\x35\x7A\x5D\x2C\x61\x24\x65\x5B\x35\x58\x5D\x2C\x61\x24\x65\x5B\x35\x59\x5D\x2C\x61\x24\x65\x5B\x35\x5A\x5D\x2C\x61\x24\x65\x5B\x31\x51\x5D\x2C\x61\x24\x65\x5B\x36\x62\x5D\x2C\x61\x24\x65\x5B\x36\x63\x5D\x2C\x61\x24\x65\x5B\x36\x64\x5D\x2C\x61\x24\x65\x5B\x36\x66\x5D\x2C\x61\x24\x65\x5B\x36\x67\x5D\x2C\x61\x24\x65\x5B\x36\x68\x5D\x2C\x61\x24\x65\x5B\x31\x73\x5D\x2C\x61\x24\x65\x5B\x35\x57\x5D\x2C\x61\x24\x65\x5B\x36\x69\x5D\x2C\x61\x24\x65\x5B\x36\x6B\x5D\x2C\x61\x24\x65\x5B\x36\x6A\x5D\x2C\x61\x24\x65\x5B\x32\x6C\x5D\x2C\x61\x24\x65\x5B\x33\x6F\x5D\x2C\x61\x24\x65\x5B\x33\x79\x5D\x2C\x61\x24\x65\x5B\x36\x6C\x5D\x2C\x61\x24\x65\x5B\x33\x67\x5D\x2C\x61\x24\x65\x5B\x33\x76\x5D\x2C\x61\x24\x65\x5B\x36\x6D\x5D\x2C\x61\x24\x65\x5B\x31\x58\x5D\x2C\x61\x24\x65\x5B\x36\x6F\x5D\x2C\x61\x24\x65\x5B\x36\x70\x5D\x2C\x61\x24\x65\x5B\x36\x6E\x5D\x2C\x61\x24\x65\x5B\x36\x72\x5D\x2C\x61\x24\x65\x5B\x33\x7A\x5D\x2C\x61\x24\x65\x5B\x36\x73\x5D\x2C\x61\x24\x65\x5B\x35\x77\x5D\x2C\x61\x24\x65\x5B\x35\x4D\x5D\x2C\x61\x24\x65\x5B\x36\x65\x5D\x2C\x61\x24\x65\x5B\x35\x69\x5D\x2C\x61\x24\x65\x5B\x35\x4C\x5D\x2C\x61\x24\x65\x5B\x32\x44\x5D\x2C\x61\x24\x65\x5B\x33\x43\x5D\x2C\x61\x24\x65\x5B\x33\x42\x5D\x2C\x61\x24\x65\x5B\x35\x6A\x5D\x2C\x61\x24\x65\x5B\x36\x71\x5D\x2C\x61\x24\x65\x5B\x35\x6C\x5D\x2C\x61\x24\x65\x5B\x35\x6D\x5D\x2C\x61\x24\x65\x5B\x35\x6E\x5D\x2C\x61\x24\x65\x5B\x35\x6F\x5D\x2C\x61\x24\x65\x5B\x35\x6B\x5D\x2C\x61\x24\x65\x5B\x35\x70\x5D\x2C\x61\x24\x65\x5B\x33\x4A\x5D\x2C\x61\x24\x65\x5B\x33\x65\x5D\x2C\x61\x24\x65\x5B\x35\x74\x5D\x2C\x61\x24\x65\x5B\x35\x68\x5D\x2C\x61\x24\x65\x5B\x35\x75\x5D\x2C\x61\x24\x65\x5B\x35\x73\x5D\x2C\x61\x24\x65\x5B\x35\x49\x5D\x2C\x61\x24\x65\x5B\x37\x69\x5D\x2C\x61\x24\x65\x5B\x35\x76\x5D\x2C\x61\x24\x65\x5B\x33\x6D\x5D\x2C\x61\x24\x65\x5B\x33\x72\x5D\x2C\x61\x24\x65\x5B\x37\x71\x5D\x2C\x61\x24\x65\x5B\x37\x6B\x5D\x2C\x61\x24\x65\x5B\x33\x69\x5D\x2C\x61\x24\x65\x5B\x37\x41\x5D\x2C\x61\x24\x65\x5B\x33\x64\x5D\x2C\x61\x24\x65\x5B\x36\x43\x5D\x2C\x61\x24\x65\x5B\x36\x45\x5D\x2C\x61\x24\x65\x5B\x33\x4D\x5D\x2C\x61\x24\x65\x5B\x36\x4E\x5D\x2C\x61\x24\x65\x5B\x36\x46\x5D\x2C\x61\x24\x65\x5B\x36\x44\x5D\x5D\x3B\x49\x20\x31\x75\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x51\x20\x48\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x5D\x5D\x28\x61\x24\x62\x5B\x30\x5D\x29\x2C\x52\x3D\x2F\x28\x5B\x5E\x7B\x5C\x7D\x5D\x2B\x28\x3F\x3D\x7D\x29\x29\x2F\x67\x3B\x32\x7A\x28\x32\x54\x20\x6F\x3D\x30\x3B\x6F\x3C\x48\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3B\x6F\x2B\x2B\x29\x7B\x51\x20\x58\x3D\x48\x5B\x6F\x5D\x5B\x61\x24\x62\x5B\x31\x5D\x5D\x28\x61\x24\x62\x5B\x33\x5D\x29\x3B\x31\x72\x28\x58\x5B\x30\x5D\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x3D\x3D\x78\x29\x7B\x31\x64\x20\x37\x51\x21\x3D\x28\x43\x3D\x58\x5B\x31\x5D\x29\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x52\x29\x26\x26\x37\x46\x28\x43\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x52\x29\x29\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x7D\x7D\x3B\x31\x64\x21\x31\x7D\x49\x20\x32\x79\x28\x29\x7B\x31\x64\x20\x61\x24\x62\x5B\x36\x5D\x2B\x31\x69\x5B\x61\x24\x62\x5B\x37\x5D\x5D\x2B\x61\x24\x62\x5B\x38\x5D\x7D\x49\x20\x34\x53\x28\x29\x7B\x31\x64\x20\x61\x24\x62\x5B\x39\x5D\x7D\x49\x20\x32\x5A\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x29\x7B\x32\x63\x28\x43\x29\x7B\x32\x6B\x20\x61\x24\x62\x5B\x31\x31\x5D\x3A\x48\x3D\x61\x24\x62\x5B\x31\x30\x5D\x2B\x78\x3B\x32\x6D\x3B\x36\x61\x3A\x48\x3D\x61\x24\x62\x5B\x31\x32\x5D\x21\x3D\x6F\x3F\x61\x24\x62\x5B\x31\x33\x5D\x2B\x43\x2B\x61\x24\x62\x5B\x31\x34\x5D\x2B\x78\x3A\x61\x24\x62\x5B\x31\x35\x5D\x2B\x78\x7D\x3B\x31\x64\x20\x48\x7D\x49\x20\x34\x4F\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x31\x64\x20\x43\x3D\x28\x43\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x31\x37\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x29\x3F\x43\x5B\x61\x24\x62\x5B\x31\x5D\x5D\x28\x61\x24\x62\x5B\x31\x39\x5D\x29\x5B\x61\x24\x62\x5B\x31\x38\x5D\x5D\x28\x29\x3A\x61\x24\x62\x5B\x32\x30\x5D\x7D\x49\x20\x34\x41\x28\x6F\x2C\x78\x29\x7B\x32\x7A\x28\x51\x20\x43\x3D\x30\x3B\x43\x3C\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x32\x31\x5D\x5D\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3B\x43\x2B\x2B\x29\x7B\x31\x72\x28\x61\x24\x62\x5B\x32\x32\x5D\x3D\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x32\x31\x5D\x5D\x5B\x43\x5D\x5B\x61\x24\x62\x5B\x32\x33\x5D\x5D\x29\x7B\x51\x20\x48\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x32\x31\x5D\x5D\x5B\x43\x5D\x5B\x61\x24\x62\x5B\x32\x34\x5D\x5D\x3B\x32\x6D\x7D\x7D\x3B\x31\x64\x20\x48\x7D\x49\x20\x34\x7A\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x31\x64\x20\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x32\x35\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x3F\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x32\x35\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x3A\x31\x69\x5B\x61\x24\x62\x5B\x32\x36\x5D\x5D\x7D\x49\x20\x34\x79\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x29\x7B\x31\x64\x20\x48\x3D\x61\x24\x62\x5B\x32\x30\x5D\x21\x3D\x31\x69\x5B\x61\x24\x62\x5B\x32\x37\x5D\x5D\x3F\x61\x24\x62\x5B\x32\x38\x5D\x2B\x31\x69\x5B\x61\x24\x62\x5B\x32\x37\x5D\x5D\x2B\x61\x24\x62\x5B\x38\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x2C\x31\x69\x5B\x61\x24\x62\x5B\x32\x39\x5D\x5D\x3F\x61\x24\x62\x5B\x33\x30\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x33\x31\x5D\x2B\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x33\x33\x5D\x5D\x5B\x30\x5D\x5B\x61\x24\x62\x5B\x33\x32\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x2B\x61\x24\x62\x5B\x33\x34\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x7D\x49\x20\x34\x77\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x2C\x52\x2C\x58\x29\x7B\x32\x6E\x3D\x61\x24\x62\x5B\x33\x35\x5D\x21\x3D\x32\x48\x20\x32\x6E\x3F\x32\x6E\x3A\x5B\x61\x24\x62\x5B\x33\x36\x5D\x2C\x61\x24\x62\x5B\x33\x37\x5D\x2C\x61\x24\x62\x5B\x33\x38\x5D\x2C\x61\x24\x62\x5B\x33\x39\x5D\x2C\x61\x24\x62\x5B\x34\x30\x5D\x2C\x61\x24\x62\x5B\x34\x31\x5D\x2C\x61\x24\x62\x5B\x34\x32\x5D\x2C\x61\x24\x62\x5B\x34\x33\x5D\x2C\x61\x24\x62\x5B\x34\x34\x5D\x2C\x61\x24\x62\x5B\x34\x35\x5D\x2C\x61\x24\x62\x5B\x34\x36\x5D\x2C\x61\x24\x62\x5B\x34\x37\x5D\x5D\x2C\x32\x45\x3D\x61\x24\x62\x5B\x33\x35\x5D\x21\x3D\x32\x48\x20\x32\x45\x3F\x32\x45\x3A\x61\x24\x62\x5B\x34\x38\x5D\x3B\x51\x20\x31\x61\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x34\x39\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x2C\x31\x63\x3D\x31\x61\x5B\x61\x24\x62\x5B\x35\x30\x5D\x5D\x28\x30\x2C\x34\x29\x2C\x31\x44\x3D\x31\x61\x5B\x61\x24\x62\x5B\x35\x30\x5D\x5D\x28\x35\x2C\x37\x29\x2C\x31\x76\x3D\x31\x61\x5B\x61\x24\x62\x5B\x35\x30\x5D\x5D\x28\x38\x2C\x31\x30\x29\x2C\x32\x66\x3D\x32\x45\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x35\x34\x5D\x2C\x32\x6E\x5B\x37\x5A\x28\x31\x44\x2C\x31\x30\x29\x2D\x31\x5D\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x35\x33\x5D\x2C\x31\x76\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x35\x31\x5D\x2C\x31\x63\x29\x3B\x31\x64\x20\x58\x3D\x31\x69\x5B\x61\x24\x62\x5B\x32\x39\x5D\x5D\x26\x26\x61\x24\x62\x5B\x32\x30\x5D\x21\x3D\x31\x69\x5B\x61\x24\x62\x5B\x35\x35\x5D\x5D\x3F\x61\x24\x62\x5B\x32\x38\x5D\x2B\x31\x69\x5B\x61\x24\x62\x5B\x35\x35\x5D\x5D\x2B\x61\x24\x62\x5B\x38\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x2C\x5B\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x35\x36\x5D\x5D\x3F\x61\x24\x62\x5B\x35\x37\x5D\x2B\x58\x2B\x61\x24\x62\x5B\x35\x38\x5D\x2B\x31\x61\x2B\x61\x24\x62\x5B\x35\x39\x5D\x2B\x32\x66\x2B\x61\x24\x62\x5B\x36\x30\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x2C\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x35\x36\x5D\x5D\x3F\x61\x24\x62\x5B\x36\x31\x5D\x2B\x31\x61\x2B\x61\x24\x62\x5B\x35\x39\x5D\x2B\x32\x66\x2B\x61\x24\x62\x5B\x36\x30\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x5D\x7D\x49\x20\x34\x4B\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x2C\x52\x29\x7B\x31\x64\x5B\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x32\x39\x5D\x5D\x7C\x7C\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x35\x36\x5D\x5D\x3F\x61\x24\x62\x5B\x36\x32\x5D\x2B\x6F\x2B\x78\x5B\x30\x5D\x2B\x61\x24\x62\x5B\x36\x33\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x2C\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x35\x36\x5D\x5D\x3F\x61\x24\x62\x5B\x36\x32\x5D\x2B\x78\x5B\x31\x5D\x2B\x61\x24\x62\x5B\x36\x33\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x5D\x7D\x49\x20\x32\x4D\x28\x6F\x29\x7B\x51\x20\x78\x3D\x28\x6F\x3D\x24\x28\x61\x24\x62\x5B\x37\x30\x5D\x29\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x6F\x29\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x37\x5D\x29\x5B\x61\x24\x62\x5B\x36\x36\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x34\x5D\x29\x2C\x43\x3D\x78\x5B\x61\x24\x62\x5B\x31\x5D\x5D\x28\x61\x24\x62\x5B\x37\x31\x5D\x29\x2C\x48\x3D\x61\x24\x62\x5B\x37\x31\x5D\x2B\x43\x5B\x61\x24\x62\x5B\x37\x32\x5D\x5D\x28\x2D\x32\x29\x5B\x30\x5D\x3B\x31\x64\x20\x39\x3D\x3D\x43\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x28\x48\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x2F\x5C\x2F\x73\x5B\x30\x2D\x39\x5D\x2B\x2F\x67\x29\x7C\x7C\x48\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x2F\x5C\x2F\x77\x5B\x30\x2D\x39\x5D\x2B\x2F\x67\x29\x7C\x7C\x61\x24\x62\x5B\x37\x33\x5D\x3D\x3D\x48\x29\x26\x26\x28\x78\x3D\x78\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x48\x2C\x61\x24\x62\x5B\x37\x34\x5D\x29\x29\x2C\x78\x7D\x49\x20\x34\x76\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x29\x7B\x51\x20\x52\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x37\x35\x5D\x5D\x3F\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x37\x35\x5D\x5D\x5B\x61\x24\x62\x5B\x31\x36\x5D\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x3B\x31\x64\x20\x43\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x37\x36\x5D\x5D\x3F\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x37\x36\x5D\x5D\x5B\x61\x24\x62\x5B\x37\x37\x5D\x5D\x3A\x61\x24\x62\x5B\x37\x38\x5D\x2C\x52\x5B\x61\x24\x62\x5B\x37\x39\x5D\x5D\x28\x52\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x2F\x3C\x34\x46\x28\x3F\x3A\x2E\x2B\x29\x3F\x34\x45\x3D\x28\x3F\x3A\x2E\x2B\x29\x3F\x28\x3F\x3A\x33\x6B\x2E\x33\x6C\x2E\x33\x6E\x29\x2F\x67\x29\x29\x3E\x2D\x31\x3F\x52\x5B\x61\x24\x62\x5B\x37\x39\x5D\x5D\x28\x61\x24\x62\x5B\x38\x30\x5D\x29\x3E\x2D\x31\x3F\x52\x5B\x61\x24\x62\x5B\x37\x39\x5D\x5D\x28\x52\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x2F\x3C\x34\x46\x28\x3F\x3A\x2E\x2B\x29\x3F\x34\x45\x3D\x28\x3F\x3A\x2E\x2B\x29\x3F\x28\x3F\x3A\x33\x6B\x2E\x33\x6C\x2E\x33\x6E\x29\x2F\x67\x29\x29\x3C\x52\x5B\x61\x24\x62\x5B\x37\x39\x5D\x5D\x28\x61\x24\x62\x5B\x38\x30\x5D\x29\x3F\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x38\x33\x5D\x2C\x61\x24\x62\x5B\x38\x34\x5D\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x38\x31\x5D\x2C\x61\x24\x62\x5B\x38\x32\x5D\x29\x3A\x32\x4D\x28\x52\x29\x3A\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x38\x33\x5D\x2C\x61\x24\x62\x5B\x38\x34\x5D\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x38\x31\x5D\x2C\x61\x24\x62\x5B\x38\x32\x5D\x29\x3A\x52\x5B\x61\x24\x62\x5B\x37\x39\x5D\x5D\x28\x61\x24\x62\x5B\x38\x30\x5D\x29\x3E\x2D\x31\x3F\x32\x4D\x28\x52\x29\x3A\x61\x24\x62\x5B\x37\x38\x5D\x7D\x49\x20\x34\x75\x28\x6F\x2C\x78\x29\x7B\x31\x64\x20\x6F\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x38\x34\x5D\x29\x3F\x61\x24\x62\x5B\x38\x35\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x7D\x49\x20\x34\x43\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x29\x7B\x31\x64\x20\x43\x3D\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x38\x36\x5D\x5D\x3F\x61\x24\x62\x5B\x34\x44\x5D\x2B\x6F\x5B\x78\x5D\x5B\x61\x24\x62\x5B\x38\x36\x5D\x5D\x5B\x30\x5D\x5B\x61\x24\x62\x5B\x34\x42\x5D\x5D\x2B\x61\x24\x62\x5B\x38\x5D\x3A\x61\x24\x62\x5B\x32\x30\x5D\x2C\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x34\x74\x5D\x5D\x3F\x43\x3A\x61\x24\x62\x5B\x32\x30\x5D\x7D\x49\x20\x34\x73\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x29\x7B\x51\x20\x52\x3D\x61\x24\x62\x5B\x32\x30\x5D\x2C\x58\x3D\x28\x78\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x2C\x34\x41\x28\x78\x2C\x43\x29\x29\x2C\x31\x61\x3D\x34\x7A\x28\x78\x2C\x43\x29\x2C\x31\x63\x3D\x34\x79\x28\x78\x2C\x43\x29\x2C\x31\x44\x3D\x34\x77\x28\x78\x2C\x43\x29\x2C\x31\x76\x3D\x34\x76\x28\x78\x2C\x43\x29\x2C\x32\x66\x3D\x34\x75\x28\x31\x76\x2C\x43\x29\x2C\x34\x5A\x3D\x34\x4B\x28\x31\x63\x2C\x31\x44\x29\x3B\x34\x43\x28\x78\x2C\x43\x29\x3B\x32\x63\x28\x6F\x29\x7B\x32\x6B\x20\x61\x24\x62\x5B\x31\x50\x5D\x3A\x43\x21\x3D\x48\x2D\x31\x26\x26\x28\x52\x2B\x3D\x61\x24\x62\x5B\x34\x4C\x5D\x2B\x43\x2B\x61\x24\x62\x5B\x34\x57\x5D\x2B\x31\x61\x2B\x61\x24\x62\x5B\x35\x64\x5D\x2B\x32\x66\x2B\x61\x24\x62\x5B\x32\x52\x5D\x2B\x58\x2B\x61\x24\x62\x5B\x35\x63\x5D\x2B\x31\x76\x2B\x61\x24\x62\x5B\x35\x62\x5D\x2B\x58\x2B\x61\x24\x62\x5B\x32\x4F\x5D\x2B\x31\x61\x2B\x61\x24\x62\x5B\x35\x39\x5D\x2B\x31\x61\x2B\x61\x24\x62\x5B\x35\x61\x5D\x2B\x34\x5A\x5B\x31\x5D\x2B\x61\x24\x62\x5B\x34\x59\x5D\x29\x7D\x3B\x31\x64\x20\x52\x7D\x49\x20\x34\x50\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x31\x64\x20\x24\x5B\x61\x24\x62\x5B\x32\x46\x5D\x5D\x28\x7B\x33\x71\x3A\x32\x5A\x28\x6F\x2C\x78\x2C\x61\x24\x62\x5B\x31\x31\x5D\x29\x2C\x34\x56\x3A\x61\x24\x62\x5B\x32\x59\x5D\x2C\x34\x4E\x3A\x21\x31\x2C\x34\x55\x3A\x61\x24\x62\x5B\x32\x58\x5D\x2C\x34\x54\x3A\x21\x30\x2C\x33\x73\x3A\x49\x28\x6F\x29\x7B\x31\x64\x20\x6F\x7D\x7D\x29\x5B\x61\x24\x62\x5B\x33\x66\x5D\x5D\x7D\x49\x20\x33\x53\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x2C\x52\x29\x7B\x48\x3D\x30\x21\x3D\x48\x3F\x48\x3A\x61\x24\x62\x5B\x34\x58\x5D\x2C\x24\x5B\x61\x24\x62\x5B\x32\x46\x5D\x5D\x28\x7B\x33\x71\x3A\x32\x5A\x28\x78\x2C\x43\x2C\x48\x29\x2C\x34\x56\x3A\x61\x24\x62\x5B\x32\x59\x5D\x2C\x34\x4E\x3A\x21\x30\x2C\x34\x55\x3A\x61\x24\x62\x5B\x32\x58\x5D\x2C\x34\x54\x3A\x21\x30\x2C\x37\x43\x3A\x49\x28\x43\x29\x7B\x32\x63\x28\x78\x29\x7B\x32\x6B\x20\x61\x24\x62\x5B\x31\x50\x5D\x3A\x6F\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x34\x53\x28\x29\x29\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x34\x52\x5D\x2B\x78\x29\x7D\x7D\x2C\x33\x73\x3A\x49\x28\x58\x29\x7B\x51\x20\x31\x61\x3D\x61\x24\x62\x5B\x32\x30\x5D\x3B\x32\x63\x28\x78\x29\x7B\x32\x6B\x20\x61\x24\x62\x5B\x31\x50\x5D\x3A\x31\x61\x3D\x61\x24\x62\x5B\x34\x51\x5D\x7D\x3B\x51\x20\x31\x63\x3D\x58\x5B\x61\x24\x62\x5B\x33\x61\x5D\x5D\x5B\x61\x24\x62\x5B\x32\x56\x5D\x5D\x3B\x31\x72\x28\x31\x63\x29\x7B\x31\x72\x28\x61\x24\x62\x5B\x31\x50\x5D\x3D\x3D\x78\x29\x7B\x31\x3D\x3D\x31\x63\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x61\x24\x62\x5B\x31\x31\x5D\x21\x3D\x48\x26\x26\x28\x31\x63\x3D\x28\x58\x3D\x34\x50\x28\x78\x2C\x43\x29\x29\x5B\x61\x24\x62\x5B\x33\x61\x5D\x5D\x5B\x61\x24\x62\x5B\x32\x56\x5D\x5D\x29\x3B\x32\x7A\x28\x32\x54\x20\x6F\x3D\x30\x3B\x6F\x3C\x31\x63\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3B\x6F\x2B\x2B\x29\x7B\x31\x72\x28\x31\x21\x3D\x31\x63\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x34\x4F\x28\x31\x63\x2C\x6F\x29\x3D\x3D\x52\x29\x7B\x31\x63\x5B\x61\x24\x62\x5B\x34\x4D\x5D\x5D\x28\x6F\x2C\x31\x29\x3B\x32\x6D\x7D\x7D\x7D\x3B\x32\x7A\x28\x32\x54\x20\x6F\x3D\x30\x2C\x48\x3D\x31\x63\x3B\x6F\x3C\x48\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3B\x6F\x2B\x2B\x29\x7B\x31\x61\x2B\x3D\x34\x73\x28\x78\x2C\x48\x2C\x6F\x2C\x43\x29\x7D\x7D\x37\x59\x7B\x51\x20\x31\x44\x3D\x21\x30\x7D\x3B\x31\x61\x2B\x3D\x61\x24\x62\x5B\x36\x33\x5D\x2C\x31\x61\x3D\x31\x44\x3F\x32\x79\x28\x29\x3A\x31\x61\x2C\x6F\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x31\x61\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x33\x52\x5D\x29\x5B\x61\x24\x62\x5B\x32\x77\x5D\x5D\x28\x29\x7D\x2C\x37\x58\x3A\x49\x28\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x32\x79\x28\x29\x29\x7D\x7D\x29\x7D\x49\x20\x35\x54\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x2C\x52\x29\x7B\x61\x24\x62\x5B\x31\x50\x5D\x3D\x3D\x78\x3F\x33\x53\x28\x6F\x2C\x78\x2C\x43\x2C\x48\x2C\x52\x29\x3A\x6F\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x32\x79\x28\x29\x29\x7D\x49\x20\x35\x4F\x28\x6F\x29\x7B\x24\x28\x6F\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x34\x5D\x2C\x49\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x31\x64\x20\x43\x3D\x61\x24\x62\x5B\x33\x55\x5D\x2C\x78\x3D\x28\x78\x3D\x28\x78\x3D\x78\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x33\x54\x5D\x2C\x43\x29\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x33\x51\x5D\x2C\x43\x29\x29\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x33\x4F\x5D\x2C\x61\x24\x62\x5B\x33\x50\x5D\x29\x7D\x29\x7D\x49\x20\x33\x70\x28\x6F\x29\x7B\x24\x28\x6F\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x2C\x78\x29\x7B\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x33\x56\x5D\x5D\x26\x26\x28\x33\x30\x2C\x78\x3D\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x33\x47\x5D\x5D\x3F\x24\x28\x61\x24\x62\x5B\x33\x45\x5D\x29\x5B\x61\x24\x62\x5B\x32\x65\x5D\x5D\x28\x29\x2B\x33\x30\x3A\x33\x30\x2C\x24\x28\x56\x29\x5B\x61\x24\x62\x5B\x33\x57\x5D\x5D\x28\x7B\x37\x57\x3A\x61\x24\x62\x5B\x33\x59\x5D\x2C\x37\x56\x3A\x78\x2C\x37\x55\x3A\x33\x30\x7D\x29\x29\x7D\x29\x7D\x32\x69\x3D\x61\x24\x62\x5B\x33\x35\x5D\x21\x3D\x32\x48\x20\x32\x69\x3F\x32\x69\x3A\x31\x69\x5B\x61\x24\x62\x5B\x34\x69\x5D\x5D\x2C\x24\x28\x61\x24\x62\x5B\x34\x70\x5D\x29\x5B\x61\x24\x62\x5B\x34\x6F\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x34\x6E\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x24\x28\x61\x24\x62\x5B\x34\x6D\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4C\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x34\x6C\x5D\x5D\x28\x31\x4B\x29\x5B\x61\x24\x62\x5B\x34\x71\x5D\x5D\x28\x61\x24\x62\x5B\x34\x6A\x5D\x2C\x61\x24\x62\x5B\x34\x68\x5D\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x32\x43\x5D\x29\x5B\x61\x24\x62\x5B\x32\x51\x5D\x5D\x28\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x33\x5A\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4C\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x34\x67\x5D\x5D\x28\x31\x4B\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x32\x43\x5D\x29\x5B\x61\x24\x62\x5B\x34\x66\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x34\x65\x5D\x5D\x28\x61\x24\x62\x5B\x32\x30\x5D\x29\x7D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x34\x64\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x24\x74\x3D\x24\x28\x56\x29\x2C\x24\x74\x5B\x61\x24\x62\x5B\x33\x41\x5D\x5D\x28\x61\x24\x62\x5B\x32\x73\x5D\x29\x3F\x24\x74\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x73\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4B\x5D\x29\x3A\x24\x74\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4B\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x73\x5D\x29\x2C\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x32\x70\x5D\x5D\x28\x61\x24\x62\x5B\x34\x63\x5D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x34\x62\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x61\x24\x62\x5B\x32\x30\x5D\x21\x3D\x32\x69\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x26\x26\x24\x28\x56\x29\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x32\x69\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x34\x61\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x51\x20\x78\x3D\x24\x28\x56\x29\x2C\x43\x3D\x78\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x32\x34\x5D\x29\x5B\x61\x24\x62\x5B\x31\x5D\x5D\x28\x61\x24\x62\x5B\x35\x65\x5D\x29\x2C\x48\x3D\x78\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x31\x74\x5D\x29\x3B\x43\x5B\x31\x5D\x26\x26\x31\x3D\x3D\x48\x26\x26\x61\x24\x62\x5B\x32\x30\x5D\x21\x3D\x28\x6F\x3D\x43\x5B\x31\x5D\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x29\x26\x26\x78\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x61\x24\x62\x5B\x33\x58\x5D\x2B\x6F\x2B\x61\x24\x62\x5B\x38\x5D\x29\x2C\x78\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x32\x34\x5D\x2C\x43\x5B\x30\x5D\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x67\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x2C\x78\x29\x7B\x51\x20\x43\x3D\x24\x28\x56\x29\x2C\x48\x3D\x43\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x32\x42\x5D\x29\x3B\x48\x26\x26\x28\x6F\x3D\x31\x75\x28\x48\x2C\x61\x24\x62\x5B\x32\x35\x5D\x29\x2C\x78\x3D\x31\x75\x28\x48\x2C\x61\x24\x62\x5B\x31\x74\x5D\x29\x2C\x30\x21\x3D\x6F\x26\x26\x43\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x4F\x5D\x29\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x6F\x29\x2C\x30\x21\x3D\x78\x26\x26\x43\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x50\x5D\x29\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x78\x29\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x51\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x29\x2C\x43\x3D\x78\x5B\x61\x24\x62\x5B\x32\x78\x5D\x5D\x28\x29\x2C\x48\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x31\x74\x5D\x29\x3B\x43\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x52\x5D\x29\x26\x26\x30\x21\x3D\x48\x26\x26\x28\x6F\x5B\x61\x24\x62\x5B\x32\x68\x5D\x5D\x28\x2F\x28\x5B\x5E\x7B\x5C\x7D\x5D\x2B\x28\x3F\x3D\x7D\x29\x29\x2F\x67\x2C\x61\x24\x62\x5B\x36\x53\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x54\x5D\x29\x5B\x61\x24\x62\x5B\x32\x68\x5D\x5D\x28\x61\x24\x62\x5B\x30\x5D\x2C\x61\x24\x62\x5B\x32\x76\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x29\x2C\x43\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x31\x74\x5D\x29\x2C\x48\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x35\x66\x5D\x29\x2C\x52\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x32\x4E\x5D\x29\x2C\x58\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x31\x4B\x5D\x29\x2C\x31\x61\x3D\x31\x75\x28\x78\x2C\x61\x24\x62\x5B\x36\x55\x5D\x29\x2C\x31\x63\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x55\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x30\x21\x3D\x58\x3F\x61\x24\x62\x5B\x36\x57\x5D\x3A\x61\x24\x62\x5B\x36\x58\x5D\x29\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x32\x76\x5D\x2C\x61\x24\x62\x5B\x30\x5D\x29\x29\x2C\x31\x63\x26\x26\x31\x63\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x59\x5D\x29\x26\x26\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x36\x5A\x5D\x29\x2C\x30\x21\x3D\x31\x61\x3F\x28\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x30\x21\x3D\x48\x3F\x61\x24\x62\x5B\x37\x61\x5D\x2B\x48\x3A\x61\x24\x62\x5B\x37\x62\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x61\x24\x62\x5B\x36\x56\x5D\x2B\x31\x61\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x32\x76\x5D\x2C\x61\x24\x62\x5B\x30\x5D\x29\x2B\x61\x24\x62\x5B\x38\x5D\x29\x29\x3A\x30\x21\x3D\x48\x26\x26\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x48\x29\x2C\x30\x21\x3D\x52\x26\x26\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4E\x5D\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x55\x5D\x2C\x61\x24\x62\x5B\x36\x4C\x5D\x2B\x52\x2B\x61\x24\x62\x5B\x36\x77\x5D\x29\x7D\x29\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x4B\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x32\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x3B\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x4A\x5D\x29\x26\x26\x28\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x36\x49\x5D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x48\x5D\x29\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x24\x28\x61\x24\x62\x5B\x36\x47\x5D\x29\x29\x29\x2C\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x42\x5D\x29\x26\x26\x28\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x50\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x29\x2C\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x41\x5D\x29\x26\x26\x28\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x36\x7A\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x50\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x29\x2C\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x79\x5D\x29\x26\x26\x28\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x37\x64\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x37\x63\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x32\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x2C\x43\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x29\x3B\x31\x72\x28\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x4D\x5D\x29\x29\x7B\x51\x20\x48\x3D\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x37\x65\x5D\x2C\x61\x24\x62\x5B\x32\x30\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x37\x6E\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x36\x33\x5D\x29\x7D\x3B\x31\x72\x28\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x37\x44\x5D\x29\x29\x7B\x48\x3D\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x37\x42\x5D\x2C\x61\x24\x62\x5B\x32\x30\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x37\x79\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x36\x33\x5D\x29\x7D\x3B\x31\x72\x28\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x37\x78\x5D\x29\x29\x7B\x48\x3D\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x37\x77\x5D\x2C\x61\x24\x62\x5B\x32\x30\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x37\x76\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x36\x33\x5D\x29\x7D\x3B\x31\x72\x28\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x37\x75\x5D\x29\x29\x7B\x48\x3D\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x37\x74\x5D\x2C\x61\x24\x62\x5B\x32\x30\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x37\x72\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x36\x33\x5D\x29\x7D\x3B\x31\x72\x28\x78\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x37\x6D\x5D\x29\x29\x7B\x48\x3D\x43\x5B\x61\x24\x62\x5B\x35\x32\x5D\x5D\x28\x61\x24\x62\x5B\x37\x6A\x5D\x2C\x61\x24\x62\x5B\x32\x30\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x37\x68\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x37\x67\x5D\x29\x7D\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x37\x45\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x3B\x51\x20\x78\x3D\x24\x28\x56\x29\x2C\x43\x3D\x78\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x37\x37\x5D\x29\x2C\x48\x3D\x78\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x37\x73\x5D\x29\x2C\x52\x3D\x78\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x32\x65\x5D\x29\x3B\x31\x57\x5B\x61\x24\x62\x5B\x37\x6C\x5D\x5D\x28\x43\x2C\x61\x24\x62\x5B\x37\x6F\x5D\x2C\x61\x24\x62\x5B\x37\x70\x5D\x2B\x48\x2B\x61\x24\x62\x5B\x37\x66\x5D\x2B\x52\x2B\x61\x24\x62\x5B\x37\x7A\x5D\x29\x5B\x61\x24\x62\x5B\x32\x51\x5D\x5D\x28\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x76\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x32\x70\x5D\x5D\x28\x61\x24\x62\x5B\x35\x4E\x5D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x74\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x2C\x78\x2C\x43\x29\x7B\x6F\x3D\x24\x28\x56\x29\x2C\x28\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x32\x64\x5D\x5D\x28\x61\x24\x62\x5B\x32\x43\x5D\x29\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x56\x5B\x61\x24\x62\x5B\x32\x57\x5D\x5D\x28\x29\x7D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x32\x64\x5D\x5D\x28\x61\x24\x62\x5B\x36\x75\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x78\x5B\x61\x24\x62\x5B\x32\x57\x5D\x5D\x28\x29\x2C\x33\x48\x5B\x61\x24\x62\x5B\x35\x4B\x5D\x5D\x28\x61\x24\x62\x5B\x35\x4A\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x53\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x55\x5D\x29\x2C\x33\x4B\x28\x49\x28\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x55\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x53\x5D\x29\x7D\x2C\x37\x53\x29\x7D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x48\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x47\x5D\x29\x3B\x78\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x28\x78\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x34\x5D\x5D\x28\x29\x2C\x43\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x32\x34\x5D\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x48\x5D\x5D\x28\x61\x24\x62\x5B\x35\x46\x5D\x2B\x78\x2B\x61\x24\x62\x5B\x35\x45\x5D\x2B\x78\x2B\x61\x24\x62\x5B\x32\x52\x5D\x2B\x43\x2B\x61\x24\x62\x5B\x32\x4F\x5D\x2B\x78\x2B\x61\x24\x62\x5B\x35\x44\x5D\x29\x7D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x61\x24\x62\x5B\x35\x43\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x42\x5D\x29\x5B\x61\x24\x62\x5B\x32\x6F\x5D\x5D\x28\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x41\x5D\x29\x29\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x7A\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x2C\x78\x29\x7B\x51\x20\x43\x3D\x24\x28\x56\x29\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x32\x42\x5D\x29\x3B\x31\x72\x28\x43\x29\x7B\x49\x20\x48\x28\x29\x7B\x31\x64\x20\x6F\x3D\x31\x75\x28\x43\x2C\x61\x24\x62\x5B\x35\x79\x5D\x29\x2C\x78\x3D\x31\x75\x28\x43\x2C\x61\x24\x62\x5B\x32\x4A\x5D\x29\x2C\x5B\x6F\x2C\x78\x5D\x7D\x24\x28\x61\x24\x62\x5B\x35\x78\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x6F\x2C\x78\x2C\x43\x2C\x52\x29\x7B\x51\x20\x58\x3D\x24\x28\x56\x29\x2C\x31\x61\x3D\x58\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x72\x5D\x29\x2C\x31\x63\x3D\x24\x28\x31\x57\x29\x2C\x31\x44\x3D\x58\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x71\x5D\x29\x2C\x31\x76\x3D\x48\x28\x29\x3B\x6F\x3D\x30\x21\x3D\x31\x76\x5B\x30\x5D\x3F\x37\x52\x28\x31\x76\x5B\x30\x5D\x29\x2B\x31\x3A\x34\x2C\x78\x3D\x30\x21\x3D\x31\x76\x5B\x31\x5D\x3F\x31\x76\x5B\x31\x5D\x3A\x31\x61\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x32\x4A\x5D\x29\x2C\x43\x3D\x31\x61\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x31\x37\x5D\x29\x2C\x30\x21\x3D\x31\x76\x5B\x31\x5D\x26\x26\x28\x52\x3D\x61\x24\x62\x5B\x31\x31\x5D\x3D\x3D\x78\x3F\x61\x24\x62\x5B\x35\x50\x5D\x3A\x61\x24\x62\x5B\x35\x51\x5D\x2B\x78\x2C\x58\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x52\x5D\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x32\x34\x5D\x2C\x52\x29\x29\x2C\x31\x63\x5B\x61\x24\x62\x5B\x33\x6A\x5D\x5D\x28\x61\x24\x62\x5B\x32\x49\x5D\x2C\x49\x20\x48\x28\x29\x7B\x31\x63\x5B\x61\x24\x62\x5B\x32\x67\x5D\x5D\x28\x29\x2B\x31\x63\x5B\x61\x24\x62\x5B\x32\x65\x5D\x5D\x28\x29\x3E\x3D\x31\x44\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x26\x26\x28\x31\x63\x5B\x61\x24\x62\x5B\x35\x53\x5D\x5D\x28\x61\x24\x62\x5B\x32\x49\x5D\x2C\x48\x29\x2C\x35\x54\x28\x31\x44\x2C\x61\x24\x62\x5B\x31\x50\x5D\x2C\x6F\x2C\x78\x2C\x43\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x55\x5D\x29\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x29\x7D\x29\x5B\x61\x24\x62\x5B\x35\x56\x5D\x5D\x28\x61\x24\x62\x5B\x32\x75\x5D\x29\x7D\x29\x7D\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x57\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x31\x75\x28\x6F\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x32\x42\x5D\x29\x2C\x61\x24\x62\x5B\x35\x58\x5D\x29\x2C\x43\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x59\x5D\x29\x3B\x32\x63\x28\x78\x29\x7B\x32\x6B\x20\x61\x24\x62\x5B\x31\x51\x5D\x3A\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x35\x5A\x5D\x29\x3B\x32\x6D\x3B\x36\x61\x3A\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x36\x62\x5D\x29\x2C\x43\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x36\x63\x5D\x29\x2C\x35\x4F\x28\x61\x24\x62\x5B\x36\x64\x5D\x29\x7D\x3B\x51\x20\x48\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x66\x5D\x29\x2C\x52\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x67\x5D\x29\x2C\x58\x3D\x6F\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x68\x5D\x29\x3B\x48\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x2C\x52\x5B\x61\x24\x62\x5B\x31\x73\x5D\x5D\x28\x29\x2C\x58\x5B\x61\x24\x62\x5B\x31\x51\x5D\x5D\x28\x29\x7D\x29\x2C\x52\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x2C\x52\x5B\x61\x24\x62\x5B\x31\x51\x5D\x5D\x28\x29\x2C\x58\x5B\x61\x24\x62\x5B\x31\x73\x5D\x5D\x28\x29\x7D\x29\x7D\x29\x2C\x24\x28\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x33\x6F\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x61\x24\x62\x5B\x36\x69\x5D\x3B\x6F\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x32\x34\x5D\x2C\x61\x24\x62\x5B\x32\x6C\x5D\x29\x5B\x61\x24\x62\x5B\x31\x74\x5D\x5D\x28\x61\x24\x62\x5B\x36\x6A\x5D\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x55\x5D\x2C\x61\x24\x62\x5B\x36\x6B\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x55\x5D\x2C\x78\x29\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x55\x5D\x2C\x78\x29\x7D\x29\x2C\x37\x4E\x28\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x33\x6F\x5D\x29\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x7C\x7C\x28\x31\x57\x5B\x61\x24\x62\x5B\x33\x79\x5D\x5D\x5B\x61\x24\x62\x5B\x32\x34\x5D\x5D\x3D\x61\x24\x62\x5B\x32\x6C\x5D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x6C\x5D\x29\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x7C\x7C\x28\x31\x57\x5B\x61\x24\x62\x5B\x33\x79\x5D\x5D\x5B\x61\x24\x62\x5B\x32\x34\x5D\x5D\x3D\x61\x24\x62\x5B\x32\x6C\x5D\x29\x7D\x2C\x37\x4F\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x6D\x5D\x29\x5B\x61\x24\x62\x5B\x33\x76\x5D\x5D\x28\x61\x24\x62\x5B\x33\x67\x5D\x29\x5B\x61\x24\x62\x5B\x32\x77\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x6E\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x24\x28\x61\x24\x62\x5B\x36\x6F\x5D\x29\x5B\x61\x24\x62\x5B\x31\x58\x5D\x5D\x28\x29\x3B\x78\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x70\x5D\x29\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x2C\x78\x5B\x61\x24\x62\x5B\x32\x6F\x5D\x5D\x28\x6F\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x71\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x24\x28\x61\x24\x62\x5B\x36\x72\x5D\x29\x5B\x61\x24\x62\x5B\x31\x58\x5D\x5D\x28\x29\x3B\x78\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x73\x5D\x2C\x61\x24\x62\x5B\x33\x7A\x5D\x29\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x31\x37\x5D\x2C\x61\x24\x62\x5B\x33\x7A\x5D\x29\x2C\x78\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x36\x65\x5D\x29\x5B\x61\x24\x62\x5B\x35\x4D\x5D\x5D\x28\x61\x24\x62\x5B\x35\x77\x5D\x29\x2C\x78\x5B\x61\x24\x62\x5B\x32\x6F\x5D\x5D\x28\x6F\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x4C\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x31\x43\x5D\x29\x5B\x61\x24\x62\x5B\x32\x70\x5D\x5D\x28\x61\x24\x62\x5B\x35\x69\x5D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x6A\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x33\x41\x5D\x5D\x28\x61\x24\x62\x5B\x32\x44\x5D\x29\x3F\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x32\x44\x5D\x29\x5B\x61\x24\x62\x5B\x32\x64\x5D\x5D\x28\x61\x24\x62\x5B\x33\x42\x5D\x29\x5B\x61\x24\x62\x5B\x33\x43\x5D\x5D\x28\x31\x4B\x29\x3A\x6F\x5B\x61\x24\x62\x5B\x31\x78\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x32\x44\x5D\x29\x5B\x61\x24\x62\x5B\x32\x64\x5D\x5D\x28\x61\x24\x62\x5B\x33\x42\x5D\x29\x5B\x61\x24\x62\x5B\x33\x43\x5D\x5D\x28\x31\x4B\x29\x7D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x6B\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x24\x28\x61\x24\x62\x5B\x35\x6C\x5D\x29\x2C\x43\x3D\x24\x28\x61\x24\x62\x5B\x35\x6D\x5D\x29\x2C\x48\x3D\x24\x28\x61\x24\x62\x5B\x35\x6E\x5D\x29\x2C\x52\x3D\x78\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3F\x78\x5B\x61\x24\x62\x5B\x31\x58\x5D\x5D\x28\x29\x3A\x21\x21\x43\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x43\x5B\x61\x24\x62\x5B\x31\x58\x5D\x5D\x28\x29\x3B\x30\x21\x3D\x52\x26\x26\x28\x52\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x35\x6F\x5D\x29\x5B\x61\x24\x62\x5B\x31\x4D\x5D\x5D\x28\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x52\x29\x29\x2C\x24\x6D\x3D\x21\x21\x48\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x26\x26\x48\x5B\x61\x24\x62\x5B\x31\x58\x5D\x5D\x28\x29\x2C\x30\x21\x3D\x24\x6D\x26\x26\x6F\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x24\x6D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x33\x45\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x31\x72\x28\x31\x3D\x3D\x31\x69\x5B\x61\x24\x62\x5B\x33\x47\x5D\x5D\x26\x26\x6F\x5B\x61\x24\x62\x5B\x32\x5D\x5D\x3E\x30\x29\x7B\x51\x20\x78\x3D\x24\x28\x33\x48\x29\x5B\x61\x24\x62\x5B\x32\x67\x5D\x5D\x28\x29\x2C\x43\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x2C\x48\x3D\x6F\x5B\x61\x24\x62\x5B\x32\x65\x5D\x5D\x28\x29\x2C\x52\x3D\x43\x2B\x48\x2B\x48\x3B\x24\x28\x31\x57\x29\x5B\x61\x24\x62\x5B\x32\x75\x5D\x5D\x28\x49\x28\x48\x2C\x58\x29\x7B\x48\x3D\x24\x28\x33\x48\x29\x5B\x61\x24\x62\x5B\x32\x67\x5D\x5D\x28\x29\x2C\x43\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x2C\x58\x3D\x24\x28\x61\x24\x62\x5B\x35\x70\x5D\x29\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x2B\x31\x2C\x48\x3E\x52\x3F\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x33\x4A\x5D\x29\x3A\x43\x3C\x3D\x58\x26\x26\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x33\x4A\x5D\x29\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x2C\x48\x3C\x78\x3F\x33\x4B\x28\x49\x28\x29\x7B\x43\x3E\x3D\x58\x26\x26\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x7D\x2C\x31\x4B\x29\x3A\x33\x4B\x28\x49\x28\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x7D\x2C\x31\x4B\x29\x2C\x78\x3D\x48\x7D\x29\x7D\x7D\x29\x2C\x33\x70\x28\x61\x24\x62\x5B\x33\x65\x5D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x73\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x36\x35\x5D\x5D\x28\x61\x24\x62\x5B\x36\x34\x5D\x29\x5B\x61\x24\x62\x5B\x35\x5D\x5D\x28\x61\x24\x62\x5B\x35\x74\x5D\x29\x26\x26\x6F\x5B\x61\x24\x62\x5B\x35\x75\x5D\x5D\x28\x61\x24\x62\x5B\x35\x68\x5D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x35\x76\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x6F\x5B\x61\x24\x62\x5B\x32\x68\x5D\x5D\x28\x2F\x28\x36\x78\x3A\x5C\x2F\x5C\x2F\x5C\x53\x2B\x28\x5C\x2E\x37\x4D\x7C\x5C\x2E\x37\x4C\x7C\x5C\x2E\x37\x48\x7C\x5C\x2E\x37\x4A\x29\x29\x2F\x67\x2C\x61\x24\x62\x5B\x35\x49\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x32\x68\x5D\x5D\x28\x2F\x28\x3F\x3A\x36\x78\x3A\x5C\x2F\x5C\x2F\x29\x3F\x28\x3F\x3A\x33\x6B\x5C\x2E\x29\x3F\x28\x3F\x3A\x33\x6C\x5C\x2E\x33\x6E\x29\x5C\x2F\x28\x3F\x3A\x37\x49\x5C\x3F\x76\x3D\x29\x3F\x28\x2E\x2B\x29\x2F\x67\x2C\x61\x24\x62\x5B\x37\x69\x5D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x33\x69\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x2C\x78\x3D\x6F\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x33\x6D\x5D\x29\x3B\x78\x26\x26\x6F\x5B\x61\x24\x62\x5B\x31\x73\x5D\x5D\x28\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x43\x29\x7B\x43\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x51\x5D\x5D\x28\x29\x2C\x24\x5B\x61\x24\x62\x5B\x32\x46\x5D\x5D\x28\x7B\x33\x71\x3A\x78\x2C\x33\x73\x3A\x49\x28\x43\x29\x7B\x51\x20\x48\x3D\x24\x28\x43\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x33\x72\x5D\x29\x3B\x48\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x37\x6B\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x37\x71\x5D\x29\x2C\x24\x28\x61\x24\x62\x5B\x33\x72\x5D\x29\x5B\x61\x24\x62\x5B\x31\x49\x5D\x5D\x28\x48\x5B\x61\x24\x62\x5B\x36\x39\x5D\x5D\x28\x29\x29\x2C\x28\x78\x3D\x24\x28\x43\x29\x5B\x61\x24\x62\x5B\x36\x38\x5D\x5D\x28\x61\x24\x62\x5B\x33\x69\x5D\x29\x5B\x61\x24\x62\x5B\x31\x70\x5D\x5D\x28\x61\x24\x62\x5B\x33\x6D\x5D\x29\x29\x3F\x6F\x5B\x61\x24\x62\x5B\x31\x73\x5D\x5D\x28\x29\x3A\x28\x6F\x5B\x61\x24\x62\x5B\x31\x51\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x37\x41\x5D\x29\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x29\x7D\x2C\x37\x43\x3A\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x33\x64\x5D\x29\x5B\x61\x24\x62\x5B\x31\x73\x5D\x5D\x28\x29\x7D\x2C\x37\x50\x3A\x49\x28\x29\x7B\x24\x28\x61\x24\x62\x5B\x33\x64\x5D\x29\x5B\x61\x24\x62\x5B\x31\x51\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x43\x5D\x29\x5B\x61\x24\x62\x5B\x33\x76\x5D\x5D\x28\x61\x24\x62\x5B\x33\x67\x5D\x29\x5B\x61\x24\x62\x5B\x32\x77\x5D\x5D\x28\x29\x2C\x33\x70\x28\x61\x24\x62\x5B\x33\x65\x5D\x29\x7D\x7D\x29\x7D\x29\x7D\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x44\x5D\x29\x5B\x61\x24\x62\x5B\x5A\x5D\x5D\x28\x49\x28\x29\x7B\x51\x20\x6F\x3D\x24\x28\x56\x29\x3B\x24\x28\x31\x57\x29\x5B\x61\x24\x62\x5B\x33\x6A\x5D\x5D\x28\x61\x24\x62\x5B\x32\x75\x5D\x2C\x49\x28\x29\x7B\x24\x28\x56\x29\x5B\x61\x24\x62\x5B\x32\x67\x5D\x5D\x28\x29\x3E\x3D\x33\x66\x3F\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x3A\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x31\x73\x5D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x3E\x3D\x24\x28\x61\x24\x62\x5B\x36\x45\x5D\x29\x5B\x61\x24\x62\x5B\x31\x4C\x5D\x5D\x28\x29\x5B\x61\x24\x62\x5B\x31\x52\x5D\x5D\x2D\x33\x36\x3F\x6F\x5B\x61\x24\x62\x5B\x59\x5D\x5D\x28\x61\x24\x62\x5B\x33\x4D\x5D\x29\x3A\x6F\x5B\x61\x24\x62\x5B\x31\x6F\x5D\x5D\x28\x61\x24\x62\x5B\x33\x4D\x5D\x29\x7D\x29\x2C\x6F\x5B\x61\x24\x62\x5B\x31\x6D\x5D\x5D\x28\x49\x28\x6F\x29\x7B\x6F\x5B\x61\x24\x62\x5B\x31\x4F\x5D\x5D\x28\x29\x2C\x24\x28\x61\x24\x62\x5B\x36\x46\x5D\x29\x5B\x61\x24\x62\x5B\x36\x4E\x5D\x5D\x28\x7B\x37\x47\x3A\x30\x7D\x2C\x37\x54\x29\x7D\x29\x7D\x29\x7D\x29","\x7C","\x73\x70\x6C\x69\x74","\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x5F\x7C\x5F\x70\x62\x74\x31\x7C\x78\x36\x35\x7C\x78\x37\x34\x7C\x5F\x70\x62\x74\x32\x7C\x78\x36\x31\x7C\x7C\x78\x36\x46\x7C\x78\x37\x33\x7C\x78\x36\x43\x7C\x78\x36\x39\x7C\x78\x37\x32\x7C\x7C\x78\x36\x45\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x33\x7C\x78\x36\x33\x7C\x78\x32\x44\x7C\x78\x36\x44\x7C\x7C\x7C\x78\x37\x30\x7C\x7C\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x34\x7C\x78\x36\x34\x7C\x78\x36\x32\x7C\x78\x32\x30\x7C\x78\x37\x35\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x35\x7C\x78\x32\x32\x7C\x78\x32\x45\x7C\x78\x36\x37\x7C\x78\x36\x38\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x36\x7C\x66\x75\x6E\x63\x74\x69\x6F\x6E\x7C\x78\x32\x46\x7C\x78\x36\x36\x7C\x78\x33\x44\x7C\x78\x37\x39\x7C\x78\x33\x43\x7C\x78\x33\x45\x7C\x78\x37\x36\x7C\x76\x61\x72\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x37\x7C\x7C\x78\x37\x38\x7C\x78\x37\x37\x7C\x74\x68\x69\x73\x7C\x78\x32\x33\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x38\x7C\x31\x30\x36\x7C\x31\x32\x35\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x31\x7C\x78\x36\x42\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x32\x7C\x72\x65\x74\x75\x72\x6E\x7C\x78\x33\x42\x7C\x78\x33\x41\x7C\x78\x37\x44\x7C\x78\x37\x42\x7C\x70\x62\x74\x7C\x78\x34\x31\x7C\x78\x32\x43\x7C\x78\x33\x31\x7C\x31\x33\x37\x7C\x78\x32\x31\x7C\x31\x33\x39\x7C\x31\x35\x34\x7C\x78\x37\x41\x7C\x69\x66\x7C\x32\x36\x38\x7C\x31\x35\x33\x7C\x67\x65\x74\x41\x74\x74\x72\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x34\x7C\x78\x34\x33\x7C\x31\x30\x37\x7C\x78\x33\x32\x7C\x78\x35\x34\x7C\x78\x33\x30\x7C\x78\x35\x33\x7C\x31\x33\x30\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x33\x7C\x78\x33\x35\x7C\x78\x36\x41\x7C\x78\x33\x33\x7C\x31\x38\x35\x7C\x31\x35\x36\x7C\x78\x34\x44\x7C\x31\x37\x30\x7C\x32\x35\x32\x7C\x31\x39\x30\x7C\x78\x34\x34\x7C\x32\x31\x33\x7C\x39\x39\x7C\x32\x36\x31\x7C\x32\x35\x31\x7C\x78\x34\x43\x7C\x78\x32\x34\x7C\x31\x37\x32\x7C\x78\x34\x41\x7C\x77\x69\x6E\x64\x6F\x77\x7C\x32\x38\x30\x7C\x78\x33\x39\x7C\x78\x34\x35\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x78\x35\x35\x7C\x78\x34\x39\x7C\x73\x77\x69\x74\x63\x68\x7C\x32\x32\x34\x7C\x31\x32\x31\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x35\x7C\x32\x35\x30\x7C\x31\x36\x35\x7C\x76\x69\x65\x77\x41\x6C\x6C\x54\x65\x78\x74\x7C\x78\x34\x46\x7C\x63\x61\x73\x65\x7C\x32\x37\x33\x7C\x62\x72\x65\x61\x6B\x7C\x6D\x6F\x6E\x74\x68\x4E\x61\x6D\x65\x73\x7C\x32\x33\x37\x7C\x31\x34\x39\x7C\x78\x32\x36\x7C\x78\x34\x45\x7C\x31\x34\x35\x7C\x78\x33\x37\x7C\x32\x34\x37\x7C\x31\x36\x36\x7C\x31\x31\x32\x7C\x31\x36\x32\x7C\x6D\x73\x67\x45\x72\x72\x6F\x72\x7C\x66\x6F\x72\x7C\x78\x35\x39\x7C\x31\x35\x38\x7C\x31\x33\x32\x7C\x32\x39\x32\x7C\x64\x61\x74\x65\x46\x6F\x72\x6D\x61\x74\x7C\x31\x30\x33\x7C\x78\x37\x31\x7C\x74\x79\x70\x65\x6F\x66\x7C\x32\x34\x39\x7C\x32\x34\x31\x7C\x31\x34\x37\x7C\x31\x32\x39\x7C\x67\x65\x74\x46\x69\x72\x73\x74\x49\x6D\x61\x67\x65\x7C\x31\x36\x39\x7C\x39\x36\x7C\x31\x38\x39\x7C\x31\x33\x31\x7C\x39\x33\x7C\x32\x32\x38\x7C\x6C\x65\x74\x7C\x32\x32\x37\x7C\x31\x30\x39\x7C\x32\x32\x33\x7C\x31\x30\x32\x7C\x31\x30\x31\x7C\x67\x65\x74\x46\x65\x65\x64\x55\x72\x6C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x31\x31\x30\x7C\x78\x33\x46\x7C\x78\x35\x32\x7C\x33\x31\x38\x7C\x33\x30\x34\x7C\x31\x30\x30\x7C\x32\x37\x37\x7C\x78\x34\x36\x7C\x33\x31\x36\x7C\x32\x35\x35\x7C\x77\x77\x77\x7C\x79\x6F\x75\x74\x75\x62\x65\x7C\x33\x31\x32\x7C\x63\x6F\x6D\x7C\x32\x37\x34\x7C\x70\x62\x74\x46\x69\x78\x65\x64\x53\x69\x64\x65\x62\x61\x72\x7C\x75\x72\x6C\x7C\x33\x31\x33\x7C\x73\x75\x63\x63\x65\x73\x73\x7C\x78\x33\x36\x7C\x78\x35\x46\x7C\x32\x37\x38\x7C\x78\x34\x38\x7C\x78\x34\x32\x7C\x32\x37\x35\x7C\x32\x38\x35\x7C\x31\x34\x36\x7C\x32\x39\x34\x7C\x32\x39\x33\x7C\x78\x33\x38\x7C\x31\x32\x32\x7C\x78\x34\x37\x7C\x31\x32\x30\x7C\x64\x6F\x63\x75\x6D\x65\x6E\x74\x7C\x78\x35\x31\x7C\x33\x30\x33\x7C\x73\x65\x74\x54\x69\x6D\x65\x6F\x75\x74\x7C\x78\x34\x42\x7C\x33\x32\x31\x7C\x78\x35\x30\x7C\x31\x31\x35\x7C\x31\x31\x36\x7C\x31\x31\x37\x7C\x31\x31\x33\x7C\x67\x65\x74\x50\x6F\x73\x74\x73\x7C\x31\x31\x38\x7C\x31\x31\x34\x7C\x31\x31\x39\x7C\x31\x32\x34\x7C\x31\x35\x35\x7C\x31\x32\x33\x7C\x31\x34\x33\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x31\x35\x37\x7C\x31\x35\x31\x7C\x31\x34\x38\x7C\x31\x35\x30\x7C\x31\x34\x30\x7C\x31\x34\x31\x7C\x31\x34\x32\x7C\x31\x33\x34\x7C\x31\x32\x36\x7C\x31\x33\x33\x7C\x78\x35\x36\x7C\x31\x33\x36\x7C\x31\x33\x38\x7C\x31\x34\x34\x7C\x31\x32\x37\x7C\x31\x32\x38\x7C\x31\x33\x35\x7C\x78\x35\x41\x7C\x67\x65\x74\x50\x6F\x73\x74\x43\x6F\x6E\x74\x65\x6E\x74\x7C\x38\x39\x7C\x67\x65\x74\x50\x6F\x73\x74\x49\x6D\x61\x67\x65\x54\x79\x70\x65\x7C\x67\x65\x74\x50\x6F\x73\x74\x49\x6D\x61\x67\x65\x7C\x67\x65\x74\x50\x6F\x73\x74\x44\x61\x74\x65\x7C\x78\x35\x37\x7C\x67\x65\x74\x50\x6F\x73\x74\x41\x75\x74\x68\x6F\x72\x7C\x67\x65\x74\x50\x6F\x73\x74\x54\x69\x74\x6C\x65\x7C\x67\x65\x74\x50\x6F\x73\x74\x4C\x69\x6E\x6B\x7C\x38\x38\x7C\x67\x65\x74\x50\x6F\x73\x74\x54\x61\x67\x7C\x38\x37\x7C\x73\x72\x63\x7C\x69\x66\x72\x61\x6D\x65\x7C\x78\x33\x34\x7C\x78\x32\x38\x7C\x78\x32\x39\x7C\x78\x32\x35\x7C\x67\x65\x74\x50\x6F\x73\x74\x4D\x65\x74\x61\x7C\x39\x30\x7C\x31\x31\x31\x7C\x61\x73\x79\x6E\x63\x7C\x67\x65\x74\x50\x6F\x73\x74\x49\x44\x7C\x67\x65\x74\x52\x65\x63\x65\x6E\x74\x50\x6F\x73\x74\x73\x44\x61\x74\x61\x7C\x31\x30\x38\x7C\x31\x30\x35\x7C\x62\x65\x66\x6F\x72\x65\x4C\x6F\x61\x64\x65\x72\x7C\x63\x61\x63\x68\x65\x7C\x64\x61\x74\x61\x54\x79\x70\x65\x7C\x74\x79\x70\x65\x7C\x39\x31\x7C\x31\x30\x34\x7C\x39\x38\x7C\x5F\x30\x78\x32\x62\x36\x62\x78\x31\x63\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x39\x37\x7C\x39\x35\x7C\x39\x34\x7C\x39\x32\x7C\x31\x35\x32\x7C\x31\x36\x38\x7C\x31\x36\x31\x7C\x33\x30\x36\x7C\x32\x39\x30\x7C\x32\x39\x35\x7C\x33\x30\x31\x7C\x32\x39\x37\x7C\x32\x39\x38\x7C\x32\x39\x39\x7C\x33\x30\x30\x7C\x33\x30\x32\x7C\x32\x34\x33\x7C\x32\x34\x32\x7C\x33\x30\x38\x7C\x33\x30\x35\x7C\x33\x30\x37\x7C\x33\x31\x31\x7C\x32\x38\x37\x7C\x32\x35\x36\x7C\x32\x34\x30\x7C\x32\x35\x37\x7C\x32\x33\x36\x7C\x32\x33\x38\x7C\x32\x33\x35\x7C\x32\x33\x34\x7C\x32\x33\x33\x7C\x32\x33\x32\x7C\x32\x33\x31\x7C\x32\x33\x39\x7C\x33\x30\x39\x7C\x32\x32\x35\x7C\x32\x32\x36\x7C\x32\x39\x31\x7C\x32\x38\x38\x7C\x32\x32\x31\x7C\x62\x65\x61\x75\x74\x69\x41\x76\x61\x74\x61\x72\x7C\x32\x34\x34\x7C\x32\x34\x35\x7C\x32\x34\x36\x7C\x32\x35\x33\x7C\x67\x65\x74\x52\x65\x6C\x61\x74\x65\x64\x7C\x32\x35\x34\x7C\x32\x34\x38\x7C\x32\x36\x39\x7C\x32\x35\x38\x7C\x32\x35\x39\x7C\x32\x36\x30\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x64\x65\x66\x61\x75\x6C\x74\x7C\x32\x36\x32\x7C\x32\x36\x33\x7C\x32\x36\x34\x7C\x32\x38\x39\x7C\x32\x36\x35\x7C\x32\x36\x36\x7C\x32\x36\x37\x7C\x32\x37\x30\x7C\x32\x37\x32\x7C\x32\x37\x31\x7C\x32\x37\x36\x7C\x32\x37\x39\x7C\x32\x38\x33\x7C\x32\x38\x31\x7C\x32\x38\x32\x7C\x32\x39\x36\x7C\x32\x38\x34\x7C\x32\x38\x36\x7C\x32\x33\x30\x7C\x32\x32\x39\x7C\x32\x32\x32\x7C\x31\x38\x31\x7C\x68\x74\x74\x70\x73\x7C\x31\x39\x33\x7C\x31\x39\x32\x7C\x31\x39\x31\x7C\x31\x38\x38\x7C\x33\x31\x39\x7C\x33\x32\x34\x7C\x33\x32\x30\x7C\x33\x32\x33\x7C\x31\x38\x36\x7C\x31\x38\x37\x7C\x31\x38\x34\x7C\x31\x38\x33\x7C\x31\x39\x35\x7C\x31\x38\x30\x7C\x31\x39\x36\x7C\x33\x32\x32\x7C\x31\x35\x39\x7C\x31\x36\x30\x7C\x31\x38\x32\x7C\x31\x36\x33\x7C\x31\x36\x34\x7C\x31\x36\x37\x7C\x31\x37\x31\x7C\x31\x37\x39\x7C\x31\x37\x33\x7C\x31\x37\x34\x7C\x31\x37\x35\x7C\x31\x37\x36\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x31\x37\x37\x7C\x31\x37\x38\x7C\x32\x31\x32\x7C\x31\x39\x34\x7C\x31\x39\x37\x7C\x32\x31\x37\x7C\x32\x31\x31\x7C\x32\x31\x30\x7C\x33\x31\x30\x7C\x32\x30\x39\x7C\x33\x31\x35\x7C\x32\x31\x39\x7C\x32\x30\x38\x7C\x31\x39\x38\x7C\x32\x31\x35\x7C\x32\x31\x36\x7C\x33\x31\x34\x7C\x32\x30\x37\x7C\x32\x31\x34\x7C\x32\x30\x36\x7C\x32\x30\x35\x7C\x32\x30\x34\x7C\x32\x30\x33\x7C\x32\x30\x32\x7C\x32\x30\x31\x7C\x32\x31\x38\x7C\x33\x31\x37\x7C\x32\x30\x30\x7C\x62\x65\x66\x6F\x72\x65\x53\x65\x6E\x64\x7C\x31\x39\x39\x7C\x32\x32\x30\x7C\x53\x74\x72\x69\x6E\x67\x7C\x73\x63\x72\x6F\x6C\x6C\x54\x6F\x70\x7C\x6A\x70\x67\x7C\x77\x61\x74\x63\x68\x7C\x67\x69\x66\x7C\x78\x35\x38\x7C\x6A\x70\x65\x67\x7C\x70\x6E\x67\x7C\x73\x65\x74\x49\x6E\x74\x65\x72\x76\x61\x6C\x7C\x31\x65\x33\x7C\x63\x6F\x6D\x70\x6C\x65\x74\x65\x7C\x6E\x75\x6C\x6C\x7C\x4E\x75\x6D\x62\x65\x72\x7C\x33\x65\x33\x7C\x35\x30\x30\x7C\x61\x64\x64\x69\x74\x69\x6F\x6E\x61\x6C\x4D\x61\x72\x67\x69\x6E\x42\x6F\x74\x74\x6F\x6D\x7C\x61\x64\x64\x69\x74\x69\x6F\x6E\x61\x6C\x4D\x61\x72\x67\x69\x6E\x54\x6F\x70\x7C\x63\x6F\x6E\x74\x61\x69\x6E\x65\x72\x53\x65\x6C\x65\x63\x74\x6F\x72\x7C\x65\x72\x72\x6F\x72\x7C\x65\x6C\x73\x65\x7C\x70\x61\x72\x73\x65\x49\x6E\x74\x7C\x7C\x7C\x7C\x7C\x7C\x7C","","\x66\x72\x6F\x6D\x43\x68\x61\x72\x43\x6F\x64\x65","\x72\x65\x70\x6C\x61\x63\x65","\x5C\x77\x2B","\x5C\x62","\x67"];eval(function(_0x8fa9x1,_0x8fa9x2,_0x8fa9x3,_0x8fa9x4,_0x8fa9x5,_0x8fa9x6){_0x8fa9x5= function(_0x8fa9x3){return (_0x8fa9x3< _0x8fa9x2?_$_pbt3[4]:_0x8fa9x5(parseInt(_0x8fa9x3/ _0x8fa9x2)))+ ((_0x8fa9x3= _0x8fa9x3% _0x8fa9x2)> 35?String[_$_pbt3[5]](_0x8fa9x3+ 29):_0x8fa9x3.toString(36))};if(!_$_pbt3[4][_$_pbt3[6]](/^/,String)){while(_0x8fa9x3--){_0x8fa9x6[_0x8fa9x5(_0x8fa9x3)]= _0x8fa9x4[_0x8fa9x3]|| _0x8fa9x5(_0x8fa9x3)};_0x8fa9x4= [function(_0x8fa9x5){return _0x8fa9x6[_0x8fa9x5]}];_0x8fa9x5= function(){return _$_pbt3[7]};_0x8fa9x3= 1};while(_0x8fa9x3--){if(_0x8fa9x4[_0x8fa9x3]){_0x8fa9x1= _0x8fa9x1[_$_pbt3[6]]( new RegExp(_$_pbt3[8]+ _0x8fa9x5(_0x8fa9x3)+ _$_pbt3[8],_$_pbt3[9]),_0x8fa9x4[_0x8fa9x3])}};return _0x8fa9x1}(_$_pbt3[0],62,503,_$_pbt3[3][_$_pbt3[2]](_$_pbt3[1]),0,{}));
//]]>
</b:tag>
<!-- Blogger Scripts -->
</body>
</html>
