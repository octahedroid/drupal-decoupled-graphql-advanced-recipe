# Drupal Decoupled Graphql advanced recipe

This recipe is a Drupal site as a turnkey solution for a headless CMS, using a GraphQL endpoint to create a decoupled site. It is ready to be seamlessly integrated with a front end application.

- For information related to installing Drupal read the [docs here](https://drupal-decoupled.octahedroid.com/docs/getting-started/drupal/install)
- For information related to installing this Recipe read the [docs here](https://drupal-decoupled.octahedroid.com/docs/getting-started/drupal/extend)

## What this recipe does:

- Adds content types `pages` and `articles`

- Create a set of `paragraphs`, ready to be used as a component for the previous content types.

- Create `media` image type

- Creates `user` roles `viewer` and `previewer`

- Creates editor `user`

- Creates default content

- Configure metatags

- Configures path auto

- Configures gin as administration experience

- Configures GQL as the decoupling strategy

  - Configures GQL Compose
    - Edges
    - Image Styles
    - Menus
    - Routes
    - Users
    - Views
    - Metatags
  - Configures preview

- Configures simple oauth as auth mechanism for the BE and the FE

- Configures Visual editor for inline editorial experience 

