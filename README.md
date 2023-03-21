Nike App Clone 
1. Mkdir 
2. Code.  
3. Npm run dev  
4. Install tailwind 
5. Change the background to BG black 
6.  
{ 
"name": "frontend", 
"version": "0.1.0", 
"private": true, 
"scripts": { 
"dev": "next dev", 
"build": "next build", 
"start": "next start", 
"lint": "next lint" 
}, 
"dependencies": { 
"@next/font": "13.1.6", 
"@reduxjs/toolkit": "^1.9.3", 
"@stripe/react-stripe-js": "^1.16.5", 
"@stripe/stripe-js": "^1.48.0", 
"eslint": "8.34.0", 
"eslint-config-next": "13.1.6", 
"next": "13.1.6", 
"react": "18.2.0", 
"react-dom": "18.2.0", 
"react-icons": "^4.7.1", 
"react-markdown": "^8.0.5", 
"react-multi-carousel": "^2.8.2", 
"react-redux": "^8.0.5", 
"react-responsive-carousel": "^3.2.23", 
"react-toastify": "^9.1.1", 
"swr": "^2.1.0" 

}, 

"devDependencies": { 
"autoprefixer": "^10.4.14", 
"postcss": "^8.4.21", 
"tailwindcss": "^3.2.7" 
} 
} 
 
7.npm I  
8.Copy paste the global.css 
9.Add eslint files 
10.Update Eslint files 
11.Add head styling Online shoe store 
12.Add Main Home Page and add import rafce 
13.In the app.js import the head from “next/head” 
14.In the theme, add fontFamily, oswald urbanist  
15.In the urbanist add urbanist and add sans-serif 
16.In the components file, Add a Footer and add a Header file 
17.Rafce and add rafce and have to make sure that the extensions are insallted 
18.Add Header into the _app.js 
19.Import Footer from “@/components/Footer” 
20. In the api and the _app.js add the </Head> 
21.Add the </Header> 
22.Add new folder pages rafce 
23.Look for the vercel.svg 
24.Category and category1.js 
25. In the Header.jsx add useState, useEffect 
26.Add const [mobileMenu,setMobileMenu] 
              const [showCatmenu,setShowCatmenu] 
              const[show,setShow]= useState(“translate”) 
              const [lastScrollY, setLastScrollY]= useState 
 
	return <div className={`w-full h-[50px]`>Header</div>; 
27.In the header.jsx import React, {useState, useEffect}  
28. Add className w-full h-[50px] to design the header 
29.md: h-[80px] 
30.Once that is created create a Wrapper.jsx and import the files necessary 
31. Add the necessary file classes that are needed 
32.Import all the images and upload the images to the src to the className=”w-40” 
33.Create a mobile menu 
34.Add menu to components file and style the menu component 
35.Then add the data and the submenu data to the file 
36.Add the necessary MetaData 
37.Create a data.map 
38. Create a react.fragment key={item.id} 
39. Make an item.submenu and li className with cursor pointer and set it = item.name 
40.Wrap it in a link component 
41.Import the menu component to the Header.jsx 
42.Add the react-icon 
43. Add the extract 
44.Add li className=”cursor=pointer” 
45.Link href= item.name 
46. Add !!item?.submenu in the data .map and add styling to the li classname 
47. Add <BsChevronDown and add showCat menu in the ul add submenudata.map 
48. Return ( 
<Link key={submenu.id} 
</Link> 
49.Add the necessary style changes to the Menu.jsx ul ClassName 
50.onMouseEnter = setShowCatMenu and add that to the onMouseEnter => setShowCountMenu 
51. OnMouseLeave = setShowCatMenu and add the setShowCountMenu 
52.Create a wrapper with a className h-60px flex justify-between items-center  
53. Add div className=”flex items-center gap-2 text-black" 
54. Add Div and add div and add <BsCart/>  
55. Add <div> 5 </div> 
56.Add className to the BsCart and add the <div>5</div> 
57. W-8 and add md: w-12 h-8 md:h-12 rounded-full flex 
58. Add more className to the text =[15px] and md: text-[20px] 
59.Bg-red-600 and add absolute top-1 and left-5 md: left-7 and a bunch of items that needed to be changed 
60. Add idtomdheartempty className and add md-[24] 
61.Add mobileMenu ? ( 
	<VsChromeClose  
		onClick={{}} => setMobileMenu 
) : ( 
	<BiMenuAllRight 
		onClick={{}} => setMobileMenu 
)} 
62.ShowCatMenu and add onClick={} 
63.MenuMobile.jsx copy paste the MenuMobile.jsx and just add the mnumobile to the const and export 
64.Add MenuMobile to the Header.jsx 
65.<MenuMobile and showCatMenu ={showcatMenu} setShowCatMenu={setShowcatMenu} 
66.SetMobileMenu ={setMobileMenu} 
67. SetMobileMenu <div  
{item.name} 
<BsChevronDown size={14}/> 
68.Add the cursor-pointer 
<Link href={item?.url} onClick={{}}=> setMobileMenu(false) 
69.In the mobile menu add the setMobile Menu to false 
70.Remove the onclick from the submenudata.map 
71.Add the flex flex-col md:hidden font-awesome 
