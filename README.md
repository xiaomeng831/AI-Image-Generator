# AI-Image-Generator
## About The Project
This is a full stack application that mimics DALL-E. 
It is built with MERN (MongoDB, Express.js, React.js and Node.js) stack.
After Users input some prompts, the back end server will call OpenAI API to let AI generate pictures. Below is the live demo website: https://ai-image-generator-xiaomeng831.vercel.app/
## Getting Started
### Server Side Installation
1. create a mongoDB database at [mongodb](https://www.mongodb.com/atlas/database) and get the connection url.
2. Get a free API at [cloudinary](https://cloudinary.com/ip/gr-sea-gg-brand-home-base?utm_source=google&utm_medium=search&utm_campaign=goog_selfserve_brand_wk22_replicate_core_branded_keyword&utm_term=1329&campaignid=18164753405&adgroupid=144188713167&keyword=cloudinary&device=c&matchtype=e&adposition=&gad=1&gclid=Cj0KCQjw2qKmBhCfARIsAFy8buINJ0q6lDFaYUOmgGzhFL9LvRyipYNp9ilqUZB0Gyg82QnD8bf-gX0aAqCiEALw_wcB)
3. Get a paid Open AI API at [OpenAI](https://openai.com/blog/openai-api)
4. set up your environment variables in `.env`
```
MONGODB_URL="enter yours"
OPENAI_API_KEY="enter yours"
CLOUDINARY_CLOUD_NAME="enter yours"
CLOUDINARY_API_KEY="enter yours"
CLOUDINARY_API_SECRET="enter yours"
```
### Server Side start
run the command: `node index.js`
### client Side start
run the command: `npm run dev`
