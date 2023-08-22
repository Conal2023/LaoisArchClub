# Laois Arch Club

[Laois Arch Club](https://conal2023.github.io/LaoisArchClub/) is a website for a local organisation for adults with intellectual disabilities. The website was set up to help promote such a good organisation that I personal have helped in the past and which family member currently siill active with their support.

People who visit the page wiLL be able to find out when the next event is, keep up to date via our social links, see the latest photos from recent event and also contact us.

![Responsive webpage on different screens](docs/screenshots/responsive.JPG)

## Features

- **Navigation Bar**

  - The Navigation bar allows users to freely flow between the 3 pages.
  - With the full responsive Navigation bar users can simply click on the links a navigate around the website.
  - Nav bar is addopted fro the Love Running project.
    ![Navigation bar](docs/screenshots/nav-bar.JPG)

- **The Header**

  - The header very simply shows the name of the organisation.
    ![Header](docs/screenshots/header.JPG)

- **Group Photo image**

  - This photo inculdes most of our members who recently attended a fundraiser for Laois Arch Club.
  - This photo shows what Laois Arch Club is all about - the members.
    ![Group photo image](docs/screenshots/group-photo.JPG)

- **What is Laois Arch Club**

  - This section gives a bit of a background about Laois Arch Club and what exactly they do.
  - Users will be able to see how the organisation gains from caring for its members and their families. This should help the organisation gain new members and new volunteers.

- **Next Event**

  - This very simply advises anyone who comes and views the page of when the next event is on. It also advises of the time and location of the event.
  - This can simply be update after each event to the next date.
    ![next-event](docs/screenshots/next-event.JPG)

- **The Footer**

  - Here links are provided to social networks sites which open in a new tab.
  - Users will be able to click on the links and a new tab will open and bring them to the relavent page.
    ![Footer](docs/screenshots/footer.JPG)

- **Gallery**

  - Here users can see some of our recent events and see the work we are doing to help our members and their family.
  - The user will benefit from this section because it will make it simple for them to understand the kinds of events that the organisation runs.
    ![Gallery](docs/screenshots/gallery.jpg)

- **Contact Us**

  - This page allows users to contact Laois Arch Club regarding joining as a member, joining as a volunteer or finding out about supporting this great cause.
  - The contact form will pop up errors if users dont fill in the required information.
  - The form is just a dummy form and doesn't actually submit any information.
    ![Contact us](docs/screenshots/contact-us.JPG)

- **Feedback**

  - This page will pop up when a user fills out the contact us form.
  - It is our way of thanking them for taking time to contact us and shows we appricate it.
    ![Feedback](docs/screenshots/feedback.JPG)

## Testing

- I have tested this web page n three different browsers and works on all: Chrome, Edge, Firefox.
- Device toolbar was also used to see the website through different screen sizes.
- All of the links on the page were tested and confirmed to be responding as they should.
- The contact us form was tested to make sure the fields that required information gave an error, the submit button tested to confirm it work and also once the submit button was ticked the feedback page responded.

## Bugs

### Solved bugs

- Throughout the project I had issues where the preview page wouldn't update after I had changed something through CSS even after a hard refresh. The first 2-3 times this happened I found it very frustrating and had to walk away from the PC for a couple of minutes. WhenI came back Codeanywhere would have signed out and I would have to sign in and open the preview page again. When the page reopened the change woud have taken place. After some digging into this through Slack chat i found out this was due to the caches on my browser. Since this whenever a change didnt take effect I would clear the caches first before making sure it wasnt something else.

- Another issue I had was when I put the box around the next event feature. This caused issues with the media feature and would cuse the box to pull far to the right away from the rest of the page. This was fixed by changing the units to a percentage rather than figure. (em,px to %). Once fixed the box appeared correctly under the media requet.

### Unsolved bugs

- I am getting a warning regarding my Google Fonts Imports advising me the "Import statements do not load in parrallel". Even though I am getting this warning the fonts are still working on the website. Upon investgation through chats with fellow students on Slack it seems a few students are also having this problem with no one able to find a solution. This will need to be investigated at a later stage.

### Validator Testing

- HTML

  - No errors were returned when passing through the official W3C validator.

- CSS

  - No errors were found when passing through the offical (jigsaw) validator.

- Accessibility

  - From running through lighthouse I confirmed that the colours and fonts chosen are easy to read and accessible.

  - Main Page Lighthouse
    ![Lighthouse Main Page](docs/screenshots/lighthouse-home.JPG)

  - Gallery Page Lighthouse
    ![Lighthouse Gallery Page](docs/screenshots/lighthouse-gallery.JPG)

  - Contact Us Page Lighthouse
    ![Lighthouse Contact Us Page](docs/screenshots/lighthouse-contactus.JPG)

## Deployment

- I deployed the page on GitHub by following the below steps:
  - Open the Setting tab in the project repository.
  - Choose the Pages tab from the menu on the left.
  - Choose the Main Branch from the drop-down option under the Source section, then click Save.
  - When a deployment to Github pages is successful, a notice will be shown with the link to the live page.

You can find the live site here [Laois Arch Club webpage](https://conal2023.github.io/LaoisArchClub/)

## Credits

- The Code Institues Love Running Project had an impact on this project. There may be some similarities in the code but I tried to stray as much as possible away from it.

- The W3Schools.com website helped me a lot when I was struggling to find a way how to do something.

## Media / Content

- The about section and all images where provided by Laois Arch Club for the website. The images would have been taken from their Facebook page which is public and members would have had to opt out of photos taken so no copy rights have been broken.
- The Favicon icon was taken from the website [favicon.io](https://favicon.io/).
- The font for the page came from [Google Font](https://fonts.google.com/).
- The icons used on the page came from [Font Awesome](https://fontawesome.com/)
- The colours ideas came from [ColorSpace](https://mycolor.space/)
