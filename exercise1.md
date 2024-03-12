# Warming up #
## Language Choice ##
Rust

## Linting ##
The Rust compiler already contains a number of lints, that are run when code is compiled. Clippy seems to be most popular tool for extra linting that can make code look and run better.

## Testing ##
Rust includes build-in support for testing. You can mark functions as tests and run them automatically. It also generates simple test function when starting a new project, that can be used as a template. Cargo (Rust package manager, similar to Node) also contains `cargo test` command out-of-box.

## Building ##
Included Rust compiler builds code into a program.

## Alternatives for Jenkins/Github Actions ##
Documentation for Cargo has some simple examples for CI https://doc.rust-lang.org/cargo/guide/continuous-integration.html

### CircleCI ###
CircleCI is a CI/CD tool that supports rapid software development and publishing. CircleCI allows automation across the user’s pipeline, from code building, testing to deployment.

### Azure DevOps ###
Azure DevOps by Microsoft is an all-in-one CI/CD platform that features entire software delivery in one place. As the name suggests, it is more than just a CI/CD tool. 

## Selfhost or Cloud ##