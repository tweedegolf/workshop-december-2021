<div class="read">

# Course overview

## Part 1: Overview of the Rust embedded ecosystem + writing a portable driver

*Exploring the basics of Rust embedded programming.*

### Learning outcomes
- Know how the ecosystem works
- Understanding how Rust drivers are used and shared

### Covered topics
- Exploring the ecosystem
  - Cortex-m crates
  - Device PACs
  - Device HALs
  - Embedded-hal
  - Typestate
  - Runtimes
- Exercise: LIS3DH ID
- Portable drivers
  - Abstraction in C
  - Abstraction in Rust
  - Low level & high level drivers
  - A low level driver in C
  - A low level driver in Rust
  - A fancy typesafe low level driver in Rust

### Assignment
Create a driver for the LIS3DH

## Part 2: A case for Rust: how to make Rust work for you in an IoT project
*Getting a feel of working with Rust is like in a larger project.*

### Learning outcomes
- Get to know commonly used tools for building, debugging and running
- Sharing code between firmware and host application and writing a common communication format.
- Writing task-based applications using RTIC

Basically, this workshops enables you to start working on production-like pure Rust IoT projects.
### Covered topics
- Making the most of Cargo
- A Rust development environment for IoT
- Knurling-rs: tools for ergonomic firmware development
- Introduction to RTIC
- Sharing code between applications

### Assignment
Case: nrf52840 communicating sensor measurements and other events to a Rust service on a host.

</div>
