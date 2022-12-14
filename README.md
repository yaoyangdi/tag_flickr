# Tag Flickr

A side full-stack project that displays images matched by tags. Visit it via https://tagflickr.netlify.app/

### User Guide

- By pressing the Enter key, you can generate a tag (repeated tag names are not allowed), then click the search icon to display results (Images matched by tags). 
- Don't know on what to search? No worries! Click the tag you are interested in under the search box and it will pop up onto the search box.
- Want to return to the home page? Click Logo "Tag Flickr" to achieve.
- Search for tags but no any associated image? Looking forward to your contribution! (via the link at the bottom of the page)

### Tech Stack

- React as the frontend framework.

- Spring boot as the backend framework.

  - Integrate Spring Boot with Hibernate for database connecting and mapping.
  
  - Utilize Cloudinary for image uploading and storing.


### TODO -> DONE

✅ Frontend:	 Home page: Searching feature

✅ Frontend:	 Tag creating page

✅ Frontend:	 Result display page

✅ Frontend:	 Deployment of frontend server  

<br>

✅ Backend:	  Upload images with tags API endpoint - POST /img

✅ Backend:	  Query all images API endpoint - GET /img

✅ Backend:	  Query all tags API endpoint - GET /tag

✅ Backend:	  Query images by tag API endpoint - GET /tag/getImagesByTag?name={tagName(s)}

✅ Backend:    Server deployment: (API documentation: https://tagflickr.herokuapp.com/swagger-ui/ )

<br>

✅ API Handling on Frontend



### UI Reference 

Home page: https://dribbble.com/shots/16941063-Crew-work-Add-tag

Tag creating: https://dribbble.com/shots/5026316-We-improved-tagging



### Future Implementation

🔲  Login authentication features for managing contribution

🔲  Light/Dark mode
