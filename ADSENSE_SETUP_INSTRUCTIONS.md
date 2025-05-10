# Google AdSense Setup Instructions

Follow these steps to set up Google AdSense on your Mayuge Light Secondary School website after deployment to GitHub Pages:

## Prerequisites
1. You need to own the domain where the site is hosted (e.g., mayugelightss.ac.ug)
2. You need a Google account
3. The website must be live and accessible

## Step 1: Create an AdSense Account
1. Go to [Google AdSense](https://www.google.com/adsense)
2. Sign in with your Google account
3. Complete the registration form with your website details and payment information

## Step 2: Verify Website Ownership
1. Google will provide you with a unique publisher ID that starts with "pub-"
2. Update the following files with your actual publisher ID:
   - Replace all instances of `ca-pub-XXXXXXXXXXXXXXXX` with your publisher ID in all HTML files
   - Update the `ads.txt` file with your publisher ID

## Step 3: Update Ad Slots
1. In your AdSense account, create ad units for different placements:
   - Homepage Top Leaderboard
   - Homepage Middle Leaderboard 
   - Homepage Bottom Leaderboard
   - In-content ads for article pages
   - Sidebar ads for wider pages
2. For each ad unit, you'll get a unique "data-ad-slot" ID
3. Replace all instances of `data-ad-slot="XXXXXXXXXX"` in the HTML files with your actual ad slot IDs

## Step 4: Verification and Approval
1. After deploying the updated site:
   - Google will review your site for compliance with AdSense policies
   - This typically takes 1-3 days but may take longer
   - Make sure your privacy policy and terms of service pages are accessible
   - Ensure ads.txt file is properly placed at the root of your domain

## Step 5: Post-Approval Optimization
1. Monitor ad performance in your AdSense dashboard
2. Consider A/B testing different ad placements for better engagement
3. Regularly check for any policy violations or warnings in your AdSense account

## Important Notes
- Do not click your own ads - this violates AdSense policies
- Ensure your site maintains high-quality, original content
- Don't place too many ads on a single page (maximum 3-4 per page is recommended)
- Make sure ads don't interfere with the user experience

## Resources
- [AdSense Program Policies](https://support.google.com/adsense/answer/48182)
- [AdSense Help Center](https://support.google.com/adsense)
- [AdSense Optimization Tips](https://support.google.com/adsense/answer/9713?hl=en)