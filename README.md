
# Ionnet.dev

2026 Version of the Ionnet Platform.

## Planned Featuresets

Public facing features:

- Home page with an overview of the platform, and its features
- Projects list
  - Individual entries of projects with the details about them, creation, usage, and more
- User profiles
  - User profiles with details about the user, their projects, and more
  - A fully customizable profile page with the ability to add custom sections, links, preset-themes, etc
- Articles written by me
  - A blog section where I can write articles about various topics related to software development, and programming
- Publicly accessible tools for achiving various tasks
- Forum for users to discuss various topics
- User accounts acts as a central authentication system for all future platforms and projects, allowing users to use the same account across all platforms and projects, and also allows for a more personalized experience across the platform
  - Integration with features for services such as Toxen and future projects.

Internal features:

- Privately accessible tools for achiving various tasks
  - These are tools that are only accessible to me, and are not meant to be used by the public, but are still hosted on the platform for my own use
- A dashboard for managing projects, users, articles, and more
- Tagging, categorization, and organization of projects, and articles
- API for projects to utilize the platform's features, such as user authentication.
  - Generation of a unique API key for each project, which can be used to access the platform's features and identify the project making the request.
  - Login page endpoint for projects to authenticate users, which can be used to create a seamless login experience for users across different projects, and the platform itself.
    - Login page redirects to the project's given redirect URL after successful login. This is redirected as a POST request with the user's information as the body of the request.
