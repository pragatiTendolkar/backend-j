# Strapi Backend -- Blog API

This Strapi backend provides the blog data for the React frontend.
The API is public, and the frontend uses only one endpoint to fetch everything.

------------------------------------------------------------------------

## About the Project


------------------------------------------------------------------------

## API Endpoints for Blogs

/blog-posts?populate=*

------------------------------------------------------------------------

## Local Setup Instructions

### 1. Clone the repository

    git clone https://github.com/pragatiTendolkar/backend-j.git

    cd backend-j

### 2. Install dependencies

    npm install

### 3. Start Strapi

    npm run develop

### 4. Admin panel

    http://localhost:1337/admin

------------------------------------------------------------------------

## Collections

### Blog Posts

-   Title
-   Slug
-   Description
-   Content
-   Featured Image
-   Category
-   Meta Title
-   Meta Description


------------------------------------------------------------------------

## Public Permissions

Make sure these permissions are enabled under **Settings → Roles →
Public**:

-   find\
-   findOne\

------------------------------------------------------------------------

## Notes

- This Strapi backend is **fully public**, so the frontend can fetch all blog data without authentication.  
- All content, images, and categories are managed through the Strapi admin panel.  
- Any updates in Strapi (new blogs, edits, or deletions) automatically reflect on the frontend via the single API.  
- Designed for simplicity and easy integration with React.