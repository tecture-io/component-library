<img alt="Tecture logo" src="https://www.tecture.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo.c2838afd.png&w=640&q=75" width="100" height="100">

# Tecture Component Library

Tecture Component Library is a community managed collections of commonly used software architectural components. 

You can use [tecture.io](https://tecture.io) to quickly create software architecture diagrams using pre-defined components from this library.

## Library Structure

Each component belongs to a collection. For an example a Lambda Function component belongs to the AWS collection. The collections are represented by folders in the root directory of the repository, while subfolders of the collection folders represent the components. Each folder contains a JSON definition file that describes the properties of each entity.

### Collection Definition

```json
{
  "name": "AWS"
}
```
- name: Name of the collection

### Component Definition

```json
{
    "name": "AWS Lambda",
    "short": "A compute service on AWS that lets you run code without provisioning or managing servers.",
    "description": "AWS Lambda is a serverless compute service allowing you to run your code without provisioning or managing servers. It executes code only when needed and scales automatically, from a few requests per day to thousands per second. It supports multiple programming languages and integrates with other AWS services. Billing is based on the compute time you consume, making it cost-effective. Its built-in security and monitoring features ensure a secure and efficient execution environment."
}
```
- name: Name of the component
- short: Short description of the component
- description: Long description of the component explaining the architectural component in detail. Please limit the text to 500 maximum characters.

Each component must contain light.svg and dark.svg files that represent the component in light and dark mode respectively.

## Contributing

If you need any new components added to the library, you can reach out to Tecture developers through the [discord channel](https://tecture.io/discord). We will try to add the required architectural components as soon as possible.

Or you could create a pull request with the new component definition to this repository and we will review and merge it.

Also, if you find any of the component definitions are incorrect or outdated, please report it through [discord channel](https://tecture.io/discord) or create a pull request with the updated definition.

~ Thank you
