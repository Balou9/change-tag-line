# change-tag-line 

coding challenge Greenbone AG 

- Create an GitHub Action that changes a line in a text file from "tag 1" to "tag 2
- Use the created action in a reusable workflow
- Utilize the reusable workflow in a GitHub repository with the GITHUB_TOKEN secret to modify this text file and commit it back to the GitHub repository using the token
- Construct a Dockerfile that incorporates this text file and upload the Docker container to ghcr.io, employing the GITHUB_TOKEN secret for authentication