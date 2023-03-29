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
93.Export const getDiscountedPricePercentage = () => { 
import the productcard and add the getDiscountedPricePercentage 
and add p.original_price, and p.price 
} 
94.Add getDiscountedPricePercentage =() => { 
const discount = originalPrice-discountedPrice 
} 
95. Return discountPercentage.toFixed(2); 
96. Const discountPercentage = (discount/originalPrice) *100 
97. Return discountPercentage.toFixed(2) 
98.Add % off 
99.In the Header.jsx add the files that are necessary  
100.Import fetchdatafromApi 
101.Const categories, setcategories = useState(null) 
102.Add useEffect(()->{},[]) 
103.const fetch categories = async () => { 
const {data}= await fetchDataFromApi(‘/api/cateogireis?populate =*') 
setCateogires(data) 
} 
104.Add fetchcategories() to the header.jsx 
105.Add categories to the menu and the mobile menu 
106.In the Menu.jsx add categories 
107.Add categories.map in the Menu.jsx 
108.Add the attributes: c,id 
109.Add id and add /cateogry/${c.slug} 
110.Add c.name  
111.Add c.products.data.length 
112.In the menu.jsx add categories 
113.Copy paste the export 
114.FetchDataFromApi and add const category await fetchdatafromapi 
115.Add const paths = category.dta.map (© 
params:{ 
slug c.attributes.slug 
return paths, 
fallback:false 
116.In the slug.js all you have to do is export async function getStaticProps({props:{slug}) 
117. Use categories?filters[slug][$eq] =jordan and add sneakers 
118.Add category = await fetchDataFromapi and add the same link 
119.Add return { 
props:{ 
category 
} 
} 
} 

120. Check the filters cateogires slug eq and sneakers 
121.Add products = await fetchDataFromApi api/products slug 
122.Add slug.js and add getStaticProps and add params: slug 
123.Add [$eq]=sneakers and add what is necessary for the link 
124.const category = await fetchDataFromApi(add the link) 
125.Const products = await fetchDataFromApi(add the link) 
126.Add category, products and slug 
127.Import category, products, and slug 
128.Import category.data[0].attributes 
129.Add products?.data?.map((product) => { 
<ProductCard key={product?.id} data={product}/> 
130.Check the link and add category and add products with the link and return { 
props:{ 
category, 
products, 
slug 
131.Add page index and add setpage index and add usestate(1) 
132.Add const data error and add useSWR (‘/api/user’, fetcher) 
133.Add the data error is loading to the useSWR add page index and add maxresult 
134.fallback products 
135.Copy paste the pagination code 
136.Change to maxResult 
137.In the pagination?.meta?.pagination?.total 
138.Import userouter and import use query= use router 
139.Import useEffect setPageindex(1) and query 
140. Change p.attributes.slug paths = category.data.map 
141. Copy paste in product and add to product 
142.Create hyperlink for products and then specifically use it for slug 
143.Add props product 
144.Export product details 
145.Fetch data api is imported 
146.const [p].data[0].attributes 
147.Product detail carousel images={p.image.data} 
148.Add image 
149.Change link in the product get static products 
150.Product detail Carousel going to add images.map ((img<imgsrc img.id}) src ={img.attributes.url} alt ={img.attributes.name} 
151. Going to add the name p.name, p.description and more 
152.For Price going to have a specific output 
152.For Price going to have a specific output 
153.Comment everything out from the product 
154. {p.size.data.map((item, i) => ( 

<div 

key={i} 

className={`border rounded-md text-center py-3 font-medium ${ 

item.enabled 

? 'hover:border-black cursor-pointer' 

: 'cursor-not-allowed bg-black/[0.1] opacity-50' 

} ${selectedSize === item.size ? 'border-black' : ''}`} 

onClick={() => { 

setSelectedSize(item.size); 

setShowError(false); 

}} 

> 

{item.size} 

</div> 
 
155.Import [const selectedsize, setselectedsize] = useState and make sure use state is imported 
156.Then we’re going to add an onclick function with the usestate const selectedsize, setselectedsize 
157.Show error and the next one is going to be setShowerror 
158. Update the selectedsize === item.size 
159.Add a border to the selected size 
160.Then add an onclick to the add to cart button and implement the usestate function 
161.{p.description} 
162.Add reactmarkdown and then add the markdown style 
163. React Redux and redux toolkit 
164.In the documentation getting started with React Redux 
165.React-Redux and create a redux store 
166.Import utils and add store frontend 
167. Add folder store to the front end  
168. Name a file store.js and import the create a redux store 
169.Import Store and Provider as well 
170. App.js import the store and import the provider and import the store properly 
171.Add the <Provider> </Provider> 
172.Implement store Provider store={store} 
173.Create a redux state slice 
174.Implement a file in the store cartSlice.js  
175. In the createSlice add name:’cart’ 
176.Import cartSlice = createSlice and add initialState, cartItems: 0 
177.Implement cartItems[] 
178.export const {increment,decrement,incrementByAmount} = counterSlice.actions 
179.Change the cartslice in the carslice.js file 
180.Can delete all the reducer method as im going to make my own 
181.addToCart: {} => { 
Import state, and add action 
} 
182. Import export const {addToCart} = cartSlice.actions; 
183.export default cartSlice.reducer; 
184.Add store.js and add cartSlice and import reducer, cart:cartslice 
185.Use redux state and actions in react components to see how we can use it. The usual is useslector, usedispatch 
186.In the products file import useSelector, useDispatch 
187.const dispatch = useDispatch() 
188.In the addtocart button add the dispatch and import in the slug.js 
189. Addto cart in the slug.js 
190. Under the scrollInto add dispatch(addToCart) 
191.cartSlice and import reducers{ 
addtocart 
} 
192.In the reducers file addtoCart add cartItems; action.payload 
193.In the dispatch(addToCart in the slug.js add product 1 
194.addtocart state.cartitems = action.payload 
195.In the provider make sure to add provider store 
197.Change dispatch to add to cart and add an else statement 
198....product? Data? .[0] 
selectedSize 
199.Then in the cart slice, set an array 
200.Install react toastify 
201.Add toastcontainer 
202.const notify = () => { 
 
 
} 
203. Install all the react toastify 
204.Add the notify button so when the add to cart button is clicked it shows the message 
205.Onequantity price in [slug].js  
206. Add const item = state.cartItems.find((p)=> p.id===action.payload 
207.if item else state.cartitems.push payload and the quantity 
208.item.quantity item attribute.price = item.oneQuantityPrice * item.quantity 
209.In the header going to add a useselector  
210. Add const {cartitems} =useSelector state and state.cart 
211.add cartitems.length>0, and then cart items.length 
212.Add leading tight 
213.Wrap up the components in the cart.jsx 
214. Add cart items to make sure that the cart is initiated 
215.Go to cartitem and change all the p names 
216.In cartitem add image 
217.add the p.size.data.map((item,I) I item.size disabled 
218.In the cartitem add const quantityarr  
219.Array.from length10,  _, I I+1 return option 1 key={1} value={q}  selected{data.queue} data.quantity =q  
220. Const updatecartitem =(e,key) and add onchange selected size 
221.let payload key, value, e.target.value add quantity  
222.parseInt 
223.Update cart and add state and action 
224.Import useDispatch and updateCart and then add updateCartItem and add useDispatch 
225.Then in the cart.slice, were going to add remove from cart  
226. Update the cart.slice function 
227.In the cartitem add updatecart, removecart 
228.Create an onclick button with dispatch  
229. In the slug.js file, add a const subTotal = use Memo  
230. Update useMemo 
231.Use the return cartItems.reduce((total,val)=> total+val.attributes.price 
232.Add subtotal to the cart.js 
233.Make an account 
234.Copy paste the code 
235.Add order.js and make sure that you convert it to USD 
236.Add the env secrets from stripe.js 
237.Update the api with an update payment request 
238.Stripe Promise update the .env  
239.const loading to cart.js 
240.Add handle payment try and catch  
241. Cart.js loading spinner


 
