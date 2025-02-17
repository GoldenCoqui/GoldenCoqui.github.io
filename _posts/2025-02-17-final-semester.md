---
title: Hello World
Date: 2024-05-10 12:00:00 -500
categories: [blog, college]
tags: [final semester, rust, blog, future]
description: Current final semester of my college experience, this is what I am up to this final semster.
image:
  path: ../assets/img/loading-grad.jpg
  alt: Graduation Loading...
---
# FINAL SEMSTER

```rust
use chrono::{NaiveDate, Utc};

fn main() {
    let target_date = NaiveDate::from_ymd(2025, 5, 9);
    let current_date = Utc::now().naive_utc().date();

    let days_left = target_date.signed_duration_since(current_date).num_days();

    println!("Days until Graduation: {}", days_left);
}


```

## 2025 is here

Since my last post I showed off all the projects I was working on, from low-level operating system projects to fun personal python projects to help me in my day to day life.
During that time I have been working on my classes, balancing retail work with an internship (System Admin intern and Software Engineer Intern) and my personal favorite working on my senior project. This post is made to give an idea of what I am up to this FINAL semester, espcecially my future career outlook and my senior project.

## Future career as a CS student

Last year I started my CS career as a System Admin intern at Leidos.  That summer experience was great as it taught me a lot about the professional world that I could not get in a classroom enviroment.  I am very appreciative of the co-workers that were patient with me asking constant questions (also if your one of them reading this, HI!). I was able to learn netowrking of systems in a large network, differnet technologies that my team was responsible of maintaining and understand the security procedures we need to follow.  I was able to show off my coding skills by creating scripts to help automate tasks, one example being a script that will communitcate with multiple servers that we maintian and do mass updates for RHEL.  One of the bigger side projects I did for System Admin team was create a better password manager that incorporated more features than the old/depreceated version had, incorporated better security/encryption coding, better shared memory feature and was made using Python so people after me can update it with ease. With that summer expereince I was able to move from a System Admin role to a Software Engineer intern role for my final Fall and Spring semester.  Currently my role as a Software Engineer intern has really put my coding/doc reading to the test but I am very happy to be a part of the team and enjoy the work I do (shout-out to my mentor).

For the future I hope to keep gaining expereience as a software engieer and learn new technologies.  My passion and attention to details has helped me move from one position to another and has helped me stay in that position with recieiving positive feedback from co-workers.  

## Senior Project 2025

Since this is my senior year I have to do a capstone project. The capstone project I am currenlty working on is an AI codebase review using the Rust language. Fall Semester my group have been creating/researching our design for this project and currenlty are now in the trenches implementing our design (with of couse the occasional headache cause of bugs).  The process is going well so far and myself and my group hope to have a final polished project at the end of April (fingers corssed). This project will also be open source so that anyone can use it.

This project was great for me because I already had an intrest in learning Rust and creating a way to automate the process of review large codebases and/or finding bugs in a codebase was something I wished I had for my current position.  I have learned so much about Rust from last year and now this year and it has made appreciate the language and what it is trying to do.  The use of a new async runtime program called Steady State was most of my reasearch time because most async runtime is done using tokio, this was an intresting challenge.  

I cannot wait to see this project avalaiable to the public and see how this project will help other programmers and contribute to the collabortive community of open source software.

## Final Semester Classes

At the moment I am doing mostly theoretical classes talking about advance algorithms, programming language structures and etc.  Currently my favorite class, becuase it incorporates theoretical with technical, is my Computer Science in Healthcare.  Where we get to learn about how to use an AI model to take data and compute it for us, currenlty it is early in the class and we are simply learning how to code/use a nueral network model to process data, but I enjoy it beccuase of the fact that it actually feels like something meaningful inside a classroom context.

