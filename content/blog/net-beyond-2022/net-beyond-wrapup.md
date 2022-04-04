# Net Beyond 2022
 

## Why F# Works in the Enterprise 

Python and Java developers are marveling over how succinct their code is now that they are using F# in a .Net ecosystem. 

"It's not like Python.Net", said Philip Carter a senior product manager at HoneyComb, "It has a heritage based on functional programming. Not out of smorgasboard programming that Python does."

Carter, who spent six years working at Microsoft, and five years working with F# for Visual Studio Code, said that F# was originally a Microsoft research project, "It's really hard for a research project to become a real product." 

According to Carter, F# provides excellent Visual Studio Code integration because it lets you use first class software development kits (SDKs) such as Badger, AWS, or any other service that has a standard .net or small library. He also talks about the benefits of *immutable First*, a feature that forces developers to structure their programming so that everything flows cleanly from top to bottom. He said that if you want to declare something as mutable, just turn off the Immutable first feature. This makes the declaration explicit, rather than everything implicitly being changeable at all times. "It's one of the reason F# programmers love using it." said Carter, especially for more complicated systems where they don't want to be debugging things all the time. 

Defining a server in F# doesn't require a lot of programming, Carter says you can do it in 11 lines of code. He also said that you can use F# to define two API routes with just three lines of code. "Anything that you can do with .net, you can do with F# on the server", says Carter.

Data analysis is another powerful feature in F# that is causing many programmers to leave Python for F# because it provides more data types, safety and performance.

Carter believes that programmers who write in C#, Java, or Python and try F# will not be disappointed. He even suggests creating a test project to test your C# and F# code because it is a good example of how to integrate an existing code base, and a great introduction to the power of F#. 

## Kubernetes Made Easy with VMware Tanzu Application Platform

Kubernetes is known for being the ultimate open-source container orchestration platform. It is also known for having a steep learning curve. 

John Bush, a senior solutions engineer at VMware, says that the learning curve is because you have to know how to deploy apps as packages in containers, usually with Docker, and because you must know how to use Yaml. "Yaml tells Kubernetes how to run your application," said Bush, adding that it also tells Kubernetes how to route, scale, event, deploy, and traffic services.  

Bush said he would like to see Kubernetes built with a higher level platform and a higher level abstraction because it is more developer friendly. He also said that developers should not have to deploy directly onto Kubernetes when it is built as a low level platform. One of the best ways to do this is to use the Tanzu Application Platform (TAP).

TAP provides customizable application accelerators that provide a starting point to buid an app. "If I was a developer who wanted to do a NET app, I would select a template accelerator," said Bush. "In TAP, you can configure the accelerator before it renders the template." The templates in TAP are sophisticated and internal to how your company does software. TAP includes a starter template. "The starter template is a skeleton," said Bush, "You can add whatever business logic you've been tasked to write."

Bush said TAP includes a Visual Studio Code plugin to enahances the local developer experience when working with an app on your desktop. "It's going to build your app and depoly it out to the development Kubernetes cluster." TAP is also going to monitor and detect source code changes, and do an incremental rebuild of the app before deploying it to your Kubernetes environment. It also gives you a live update of code change and monitors your environment without having to invoke commands. "As I make changes, it rebuilds and deploys my app," says Bush, "I can just focus on code and not worry about issuing commands."

## Mobile DevOps at Scale

Continuous integration (CI) is universal. With it, you can restore, build, publish and release. When you deploy software as a service (SaaS), you are on the most recent version of the app, unless you are looking at the app in a mobile device. 

"There is no guarantee that any given end user is going to be on the most recent version of the apps," said Rodney Littles II, a senior software engineer who is currently working with Xamarin mobile and Azure cloud infrastructure. Littles says it's important to be mindful of this caveat whenever talking about CI if you are deploying SaaS to AWS and others. You don't have failovers to go back to the previous version. The only way to get this to work is to fail forward. "That means you have to push a binary with the previous version, with a new version number that is greater than the one that you want to get rid of, " said Littles.

When comparing mobile to an old school desktop, Littles said that it's very important to make sure that you have side-by-side installations from day one to avoid increasing CI risk and landscape. He suggests using MSBuild from a command line because a dotnet cli does not exist. The key is to ensure that the binaries are signed. "You can't deploy an IOS app to a mobile phone if the binaries are not signed," he said, because mobiles are specific. 

When writing his apps, Little said he prefers Nuke over YAML because Nuke is an extensible, domain specific language that can generate a YAML file from a build script. Nuke is also an abstraction that sits on top of MSBuild. Another reason Littles said he chose Nuke is because he likes partial classes that he can separate and segregate because it gives him separation of concern. "Single responsibility is my jam. It is the most solid principle, but also the most violated principle."

## ASP.NET - Basics for Experts 


by Layla Porter and Jakub Pilimon

People love to stay in their comfort zone; but what if you have to step outside of it and embrace a new programming language, one that happens to be ASP.NET?

Jakub is a Java/Spring developer and architect. He’s never used ASP.NET before and he has questions. Lots of questions.

Layla, a .NET developer, intends to answer Jakub’s questions and more in this demo-rich session.

But don’t worry, there will also be something for existing ASP.NET developers as we delve into the ways an ASP.NET application is configured to support services:

Dependency injection and inversion of control
HTTP clients and policies
Resiliency and circuit breakers
Databases connections
Discovery clients
And more!
