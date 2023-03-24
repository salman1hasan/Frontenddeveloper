Nike App Clone [Frontend development] 
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
72.Copy paste the footer, in the footer.jsx add the window.open function 
73. Add facebook and add _blank 
74. Create HeroBanner and add it to the index.tsx 
75.Install react responsive carasouel 
76. Add needed style to herobanner.jsx 
77.Import the necessary images and style the components 
78. In the carousel autoplay={true} infiniteLoop={true} showThumbs={false} showIndicators={false}/> 
79.Index.tsx add the wrapper and add the <div></div> 
80.In the index.tsx add div className and add grid </div> 
81.Add productcard rafce 
82. Add productcartid import link and import react 
83. Import the image necessary for productcard id 
84. <p className add all the text 20%/> 
85.Add transform property to create an effect for the product 
86.In the category file add a pages and import the category [slug].js 
87.Dynamic Routing explained 
88.Have to add the slug to the file 
89.Add the wrapper and add two div classNames Running Shoes 
90.Create a product and add <div className slug.js> 
91.The div adding a div is important to make sure that the two columns are perfectly aligned 
92.Create Product details carousel 
93.Import the images that are necessary 
94.Add product details in the slug.js 
95.A bunch of details the most important is the sizes as you have to add all the sizes 
96. Add size selection to the slug.js 
97.Create two buttons Add to Cart and Wishlist 
98.Add div className and set it = to productdetails 
99.Add a bunch of text 
100. Add related products and add slug.js 
101. Add product card to the file 
102.Create a file Cart.js 
103.Add a header and change the and change the menu button 
104.Create a shopping cart file and then from there add cart items and add summary 
105.Import cartItems 
106.Add div className and add the items for the caritem 
107.Create a dropdown menu for the size of the components 
108.Add another quality and add components to the file 
109.Add the Bin button and make sure that you hide the button in the right place 
110.Add cart.js add memory Summary 
111.Subtotal and 20,000 and then add button className 
112.Add an image at the end 
113.Add a message for where it says that the cart is empty 
114.Add a link for contining to shop 
115.Add failed.js data 
116.Add success.js file as well 
 

 
Nike App Clone [Backend development] 
1.Create Backend folder 
2.Cd backend folder 
3.Npx create-strapi-app@latest 
4.Custom settings 
5. JS, and postgres 
6.Create an account on render.com 
7.Click on PostgreSQL 
8. Add the name and add the region that is near and make sure its free 
9.Connections Copy and paste the database name from render and import it to the backend 
10. Copy paste the external database url and and copy paste after the @ sign to the render.com 
11.Host name copy and paste the code 
12. Copy and paste the port 
13. Add the userName 
14. Add the password from the render.js file 
15.Enable the SSL connection 
16.NPM run develop 
17. Add the name last name email password and confirm password 
18.Go to cloudinary and import the cloudinary image 
19.Make a cloudinary account 
20.Add strapi dashboard in marketplace and add cloudinary copy install 
21.npm install @strapi/provider-upload-cloudinary 
22.Strapi.io/ plugin 
23. Have to follow the instructions and add ./config/plugins.js and copy paste the code 
24. Add a file plugins.js and copy paste the code 
25.Remove strapi security and add fixing preview issue on strapi admin 
26. Add the cloudinary functions to the .env file 
27. Copy paste the name, key and the secret 
28. Npm run develop 
29.Upload an image to the desktop 
30.It should be uploaded to the assets 
31.Create collection type for strapi 
32.Add user fields 
33. Create a new collection type 
product and this adds the products 
34.Advanced settings add nothing 
35.Text field and add name(Short text), in advanced settings for product can change the values 
36. In the product, name needs to be required 
37. Add subtitle and add number field and add price and number format and add decimal 
38.Add required field and add another field 
39. Add rich text and add name and add description and add another field 
40.Size  
41. Image and in advanced settings only add images 
42.Product field add thumbnail and make it a required field and only images 
43.In product add original price and add decimal for this one need a slug and need to add UID 
44.Add Slug and add name 
45. Add category and add products and add category belonds to many products 
46. Add order, order category and add order AppID order 
47.Add text field and add stripeId and add require field and products 
48.Download the images shoe-store-product-images.zip 
49.Create a product and add the original price and air-jordan-1-mid-se 
50.Update all the categories and push the air jordan 1 mid se 
51.Make sure that it can all be uploaded on all categories 
52.Update the jordan categories 
53.In the api tokens create and add shoe store and add full access 
54.Copy paste the key 
55.In the apitokens add shoe store 
56. Download Insomnia 
57.http://localhost:1337/api/products 
58.Bearer Token and add the token  
59.Can use different routes as well 
60.Add public ramadan find and findone 
61.Add a .env file NEXT_PUBLIC_STRAPI_API_TOKEN and add token 
62.Utils and add urls 
63. Const Strapi_API_Token = process.env.NEXT_PUBLIC_STRAPI_API_TOKEN 
64. Const API_URL = process.env.NEXT_PUBLIC_API_URL || “http://localhost:1337/” 
65.Add the 127.0.0.0 
66.Add api.js and add api_url, strapi_api_token =”./urls’ 
67. Const fetchDataFromApi and get the uri and import in the api.js 
68. Add endpoint and add const res = await fetch(`${API_URL}${endpoint}`} 
69. Const data = await res.json(); 
70. Return data and add export const fetchDataFromApi 
71.Index.js and add const[data,setData]= useState(null) 
72.useEffect and add const fetchProducts =() => { 
import fetchDataFromApi 
} 
73. Const {data} = await fetchDataFromApi(‘/api/products’) 
74.setData(data) 
75.Add data [0] attributes and name 
76.Check in the components 
77.Have to fetch the data from nextjs using getServerSideProps, this is the way to get the server 
78.Remove the data and the setdata 
79.Import the const products = await fetchdataFromApi and add api/products 
80. Add erturn props{products} 
81.Export function Home products 
82.Remove the h1 and the productCart 
83.Add products.data.map((product) => )} 
84.key ={product.id} and add data={map} 
85.Add productCard and add data 
86.attributes:p, id in the product card 
87.In the Link href={1/products/${p.slug}`} 
88.Add image width height src and add the necessary p tags for the name price  
89.Change the index.js for the api/products and populate 
90.Nextconfig add eslint and add ignore during builds 
91. Add images domains[“res.cloudinary.com”] 
92.Add file helper.js 
 
