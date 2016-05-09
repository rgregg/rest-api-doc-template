# REST API documentation template

This repository provides a template for creating testable documentation for a REST API using [Markdown Scanner][1] and Markdown.

When we started out to build the [OneDrive API][2] we knew it was important to have great documentation available for the API in addition to a simple, well
designed API surface. To accomplish this, we evaluated a number of tools for writing API documentation and best practices from other teams and created a
unique process that we use now to ensure we have high quality APIs and documentation.

Our process treats the documentation as the single source of truth for our API. Following this, if it isn't documented it doesn't exist. We start off writing the
developer documentation for a new API, refining the design, and then writing the code for the API and using the documentation to validate the implementation. Our
tools also allow the documentation to be transformed into other formats as necessary while preserving the *single source of truth* goal.

## Getting Started

This repository has two folders, which can be used to organize your content. A folder for [resources](resources) which we use to store the definitions for resources
in the API, and a folder for [apis](apis) where the various API calls your API supports can be documented.

### Resources

A resource defines the response from an API call, such as an item, an event, or a message. The resource documentation describes the shape of the resource (usually
in JSON) and the properties / details of those resources.




[1]: https://github.com/onedrive/markdown-scanner
[2]: https://dev.oendrive.com
