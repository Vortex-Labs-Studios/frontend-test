## Vortex Front-end Technical Interview Test

### CATKNOW

Create a cat encyclopedia web app with two pages powered by The Cat API. The first page is an infinite scrolling list showing cats images and their names. When clicking on a specific cat image, a second page should open, showing more detailed information about the clicked cat.

- In desktop, show a grid with 4 columns.
- In tablet, user can see only a grid with 2 columns.
- In mobile, user can see only a grid with 1 column.

The API documentation is: https://developers.thecatapi.com/view-account/ylX4blBYT9FaoVd6OhvR?report=bOoHBz-8t

- To fetch images list: https://api.thecatapi.com/v1/images/search
- To fetch categories list: https://api.thecatapi.com/v1/categories
- To get specific cat: https://api.thecatapi.com/v1/images/<ID>

User must be able to filter cats by CATEGORY by clicking the Chips in the first page.

Here's a Figma link with moockup design examples, feel free to use it or create something else: [FIGMA](https://www.figma.com/design/O59cTYodflm2C6VozQRV9v/Untitled?node-id=0-1&t=r8jUUjbanMo3Jrf5-1)

## Technology Stack

Must be done using NextJS, either with `pages router` or `app router`. Language of choice is Typescript.
Project should be commited to a Github repository.
