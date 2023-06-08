# Cloud Hosting and Learning Optimization Environment (CHLOE)

**Disclaimer:** This is very much a work-in-progress. All design, documentation,
etc. is written from the point of view of a completed product..._which CHLOE is
far from_. Currently I am working on migrating some development work from
another repository to this organization, in the hopes that others who are
interested in AWS and/or game development can contribute ideas, code, or
anything else.

The [unity-project](https://github.com/chloe-game/unity-project) repository
contains the current source code for the proof of concept game.

At the moment, my goal is to build out
[Level 0](https://github.com/chloe-game/documentation/blob/main/design/levels/00-s3.md)
and have players give feedback on the concept as a whole.

---

## What if you could physically walk through an AWS account?

Cloud Hosting and Learning Optimization Environment (CHLOE) is game-based
training simulation for visual learners. CHLOE's single-player, story-driven
game teaches players core AWS services, concepts, and best practices using the
[AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/).
In Simulation Mode, players can use CHLOE to render AWS accounts as 3D
environments where they are able to view, launch, update and terminate resources
in real-time. CHLOE provides contextual training to solve real-world problems
through audiovisual explanations and tutorials, as well as animated architecture
demonstrations.

Current Cloud training focuses on text-/console-based tasks. Cloud architecture
is often restricted to static, 2D diagrams. This does not always lend itself
well to the many resources and relationships involved in building on AWS.
Searching for answers online lacks important context, and existing training
requires users dedicate time away from building. Making decisions and
communicating architecture designs across multiple teams and organizations has
been an ongoing challenge with existing tools, which lack fidelity and reduce
the data available to decision-makers.

The story of CHLOE's Game Mode starts with a data center incident causing the
player to be stuck inside their company's AWS account. To return to the real
world, the player must rebuild their company's broken applications on AWS using
the Well-Architected Framework. As a separate experience, Simulation Mode lets
players design solutions and get contextual answers to complex scenarios.
Players can use existing accounts to build dynamic, 3D architecture diagrams and
live workloads in real-time.

In Game Mode, players earn badges by completing tasks, which can be used to
showcase their knowledge to the AWS community. In Simulation Mode, players can
create 3D architecture diagrams, or synchronize with their AWS accounts in
real-time. View filters for the Well-Architected Pillars provide feedback on
areas of strength or improvement. Players can use the in-game assistant, CHLOE,
for just-in-time (JIT) training, providing contextual information while
building.

- [Frequently Asked Questions (FAQ)](https://github.com/chloe-game/documentation/blob/main/design/faq.md)
- [Example Intro Level Outline](https://github.com/chloe-game/documentation/blob/main/design/intro-level-outline.md)

## Why is this important?

### Existing hands-on training does not appeal to visual or spatial learners

Technical training is often prescriptive and lacking visual fidelity. Hands-on
training such as self-paced labs are typically single-service in focus, with
relationships and integrations into workloads being represented as static
architecture diagrams.

### Customers want human-readable, meaningful architecture visualization

Multi-account and multi-region infrastructure do not scale in existing 2D
visualizations without loss of fidelity or data. Customers cannot make fully
informed decisions when data is sacrificed for comprehension. Web-based
visualization tools lack sufficient processing power to render large
infrastructure sets in a meaningful way. Creation of architecture diagrams by
hand is time consuming and error prone. Existing tools such as the AWS
Management Console, AWS Command Line Interface (AWS CLI), and AWS software
development kits (SDKs) provide text-based output that is well-suited for
computational processing, but less so for human comprehension. Video
game/simulation engines provide an opportunity due to their built-in
optimization for handling large numbers of interrelated objects that interact in
real-time.

### Customers frequently have to switch contexts between learning and doing

Existing simulation and training technologies are one-way, read-only systems
that require context switching to and from in order to view information, make
decisions, and take action on those decisions. There is an opportunity to reduce
customer churn between systems in order to make infrastructure decisions and
take action.

---

## Contribute

I come from what I like to think is a decent DevOps background. I can generally
pick up a cloud service and make it do something that resembles useful work.
Unity and C# are a new area, though.

If you're interested in contributing to the game asset fund, please use any of
the links below. Donations would be used solely for the purchase or license of
assets and code that will either be part of CHLOE itself or part of what brings
CHLOE to life.

[![Buy Me a Coffee](https://img.shields.io/badge/buymeacoffee-ncalteen-orange)](https://www.buymeacoffee.com/ncalteen)
[![PayPal.Me](https://img.shields.io/badge/paypal-ncalteen-blue)](https://paypal.me/ncalteen)
[![Coinbase](https://img.shields.io/badge/coinbase-0x5b340de3738613c94e2f624e2c30db5627fa4cc8-red)](0x5b340de3738613c94e2f624e2c30db5627fa4cc8)

If you have experience in literally any of the below and want to contribute time
instead, please do! Any and all PRs will be reviewed and, _given the high chance
they're better than any code I could write_, likely merged.

- AWS (particularly the below to start)
  - Amazon S3
  - AWS IAM
  - Amazon VPC
  - Amazon EC2
  - AWS Auto Scaling
  - AWS Lambda
  - Amazon DynamoDB
  - Amazon RDS
  - Amazon SNS
  - Amazon SQS
  - Amazon CloudWatch
- Animation
- Audio effects
- Build/release management
- Character design
- Game AI
- Game asset management and source control
- Game data/metrics collection
- Game design
- Game physics
- Game save data management
- Level design
- Music composition
- Particle effects
- Player control
- Story writing
- Technical writing
- UI development
- Unity performance optimization
- UX development
- VR development
