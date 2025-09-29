# GoMock: Replacing Hand-Coded Test Doubles in Golang
This repository contains the refactored code for The Engineering Coach's video, which demonstrates the transition from custom, hand-coded Test Doubles to the use of the GoMock mocking framework.

This is a crucial step in a professional Golang TDD workflow, showing you how to maintain the benefits of test isolation while dramatically reducing boilerplate code.

## 📺 Watch the Video
This code is a practical demonstration of how to implement a mocking framework.

➡️ Watch the video: GoMock: Replacing Hand-Coded Test Doubles in Golang

[![GoMock: Replacing Hand-Coded Test Doubles in Golang](https://img.youtube.com/vi/FoMMbZJmg6o/0.jpg)](https://www.youtube.com/watch?v=FoMMbZJmg6o)

## 💡 What This Code Demonstrates
  - Efficiency over Manual Implementation: See the before-and-after comparison of using hand-coded Mocks versus framework-generated Mocks.
  - GoMock Integration: Learn how to install and integrate the GoMock framework into your Golang project.
  - Refactoring for Cleanliness: Understand how to refactor your tests to be more expressive and concise using framework assertions and expectations.

## 🚀 Getting Started with the Code
Clone the repository:

git clone [https://github.com/testingallthethings/031-gomock](https://github.com/testingallthethings/031-gomock)
cd 031-gomock

Generate Mocks (Crucial Step):
GoMock uses a code generator to create the necessary mock files.

```shell
go generate ./...
```

Run the entire test suite:

```shell
go test ./...
```

🔗 Context & Foundational Videos
This video is a direct follow-up to our series on building test doubles from scratch. If you missed the foundation, start here:

➡️ Watch the full Golang Test Doubles playlist here!

## About The Engineering Coach
The Engineering Coach is a YouTube channel dedicated to helping software engineers and engineering managers improve their skills and craft. We provide practical advice and tutorials on topics that matter in the real world of software development.

## Let's Connect
For more software engineering tutorials and coaching, subscribe to The Engineering Coach on YouTube. You can also connect with me on Bluesky or Mastodon.

  - YouTube: [https://www.youtube.com/c/TheEngineeringCoach](https://www.youtube.com/c/TheEngineeringCoac)
  - Mastodon: [https://mastodon.social/@braddle](https://mastodon.social/@braddle)
  - Bluesky: [https://bsky.app/profile/braddle1.bsky.social](https://bsky.app/profile/braddle1.bsky.social)
