---
layout: post
title: 'Blog.Says("Hello, World!");'
author: Tanner Gooding
date: 2019-03-02
---

<p>After much internal debate, I finally decided to start a blog and currently plan on posting about things that come up when coding both at work and in personal projects.</p>

<p>I first joined Microsoft as vendor in 2012 doing work for the Roslyn team. Almost 3 short years later I was hired as a full-time employee to the same team and got the privilege of helping move Roslyn onto GitHub. Over the next three years I got to work on various bits of Roslyn infrastructure, the initial version of Live Unit Testing, making the Roslyn Project System more accessible, and more infrastructure work in the .NET Core SDK.</p>

<p>Performance, numerics, "low-level" scenarios, and the latest tools have always piqued my intereset and I eventually migrated over to the CoreFX team so that I could have a broader impact in these areas. But, even before I joined the team directly I was trying to make meaningful contributions. One of my first contributions was removing some legacy workarounds from the `System.Math` code (<a href="https://github.com/dotnet/coreclr/pull/4847">dotnet/coreclr#4847</a>). This contribution was my first real dive into CoreCLR/CoreFX and got me comfortable enough with the codebase that I went on to add several other meaningul contributions, including:</p>
<ul>
  <li>The <code>System.MathF</code> class (<a href="https://github.com/dotnet/coreclr/pull/5492">dotnet/coreclr#5492</a>),</li>
  <li>The initial support for building with VS2017 (<a href="https://github.com/dotnet/coreclr/pull/9956">dotnet/coreclr#9956</a>),</li>
  <li>Helping start the Hardware Intrinsics feature (<a href="https://github.com/dotnet/coreclr/pull/15341">dotnet/coreclr#15341</a>), and</li>
  <li>Working on making the floating-point parser/formatter IEEE compliant (<a href="https://github.com/dotnet/coreclr/issues/19802">dotnet/coreclr#19802</a>)</li>
</ul>

<p>I am currently planning on my next blog post being about how the <code>System.Math</code>/<code>System.MathF</code> calls work and how the cross-platform differences are partially normalized. I would also like to do a write-up on the hardware intrinsics feature and some of the feature-requests I would most like to see in the framework, runtime, and languages, but we'll see how that turns out.</p>
