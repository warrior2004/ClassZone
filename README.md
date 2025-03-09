## Project Deployment
This project is deployed and can be accessed at [Deployment Link](https://class-zone.onrender.com).

The app might run slow on the first load as it is deployed on a free plan.

## Getting Started

To get started, just clone the repository and run `npm install`:

    git clone https://github.com/mastermanav09/ClassZone.git
    npm install

    ## Dependencies


## This project relies on the following external services:

### MongoDB:

MongoDB is used as the database for storing and retrieving data.

### Cloudinary:

Cloudinary is used for managing and serving media assets such as images and files.

### Google Auth:

Used for Authentication.

## Setup

To run this project locally, you need to set up MongoDB, Cloudinary and Google O-Auth and provide the necessary API keys.

### MongoDB Setup

1. Install MongoDB on your machine.
2. Create a new MongoDB database for this project.

### Google Auth

1. Create your credentials here [Google API](https://console.cloud.google.com/apis).

### Cloudinary Setup

1. Sign up for a [Cloudinary account](https://cloudinary.com/users/register/free).
2. Obtain your Cloudinary API key, API secret, and cloud name.
3. Create a `.env` file in the project root and add the following information:

```env
MONGODB_URI=your_mongodb_connection_string
GOOGLE_ID=your_google_auth_id
GOOGLE_SECRET=your_google_auth_secret
SECRET=your_jwt_secret
NEXTAUTH_URL=your_base_url
NEXT_PUBLIC_NEXTAUTH_URL=your_base_url
NEXTAUTH_SECRET=your_next_auth_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_api_secret
CLOUDINARY_UPLOAD_PRESET=your_cloudinary_upload_preset
CLOUDINARY_URL=cloudinary://my_key:my_secret@my_cloud_name
UPLOAD_CLOUDINARY_URL=https://api.cloudinary.com/v1_1/${my_cloud_name}/upload
```

## Running locally in development mode

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
