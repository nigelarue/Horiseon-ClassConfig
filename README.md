<!-- # Horiseon-Repo
Challenge 1 repository upload.
File is an HTML website given by our instructors to clean out redundant code. 
Removed redundant h3 and img lines for benefit, added benefit class to html in order to reflect updates as well as updated images to reflect accessible alt image text. Removed redundant image assignments in css stylesheet.

Removed the following lines:

.benefit-lead h3 {
   margin-bottom: 10px;
   text-align: center;
}
 
.benefit-brand h3 {
   margin-bottom: 10px;
   text-align: center;
}
 
/* .benefit-cost h3 {
   margin-bottom: 10px;
   text-align: center;
} */
/* Removed duplicate code */

Replaced with and updated font color: 

.benefit h3 {
   margin-bottom: 10px;
   text-align: center;
   margin-bottom: 32px;
   color: #ffffff; 
}

Updated HTML to reflect new benefit class:

     <div class="benefit">
           <h3>Brand Awareness</h3>
           <img src="./assets/images/brand-awareness.png" />
           <p>
               Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
           </p>
       </div>
       <div class="benefit">
           <h3>Cost Management</h3>
           <img src="./assets/images/cost-management.png" />
           <p>
               As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
           </p>
       </div>

Updated images to have alt text:

           <img src="./assets/images/search-engine-optimization.jpg" class="float-left"alt="image with a notepad regarding SEO" />
           <h2>Search Engine Optimization</h2>
           <p>
               The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
           </p>
       </div>
       <div id="online-reputation-management" class="online-reputation-management">
           <img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="image with of a laptop with 'reputation' at the top" />
           <h2>Online Reputation Management</h2>
           <p>
               The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
           </p>
       </div>
       <div id="social-media-marketing" class="social-media-marketing">
           <img src="./assets/images/social-media-marketing.jpg" class="float-left" alt="image with various social media phrases" /> -->

Removed the following lines to consolidate:
/* 
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
} */
