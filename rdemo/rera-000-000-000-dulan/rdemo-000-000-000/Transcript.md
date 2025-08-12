# Transcript
- **Authors:** [Liam Monninger](mailto:liam@ramate.io)

<!-- ltex: enabled=false -->
<!-- vale off -->
00:00 Hey everybody, I'm gonna talk quickly through the Remate repository, provide a demo of how to use it, uhm, the bottom line is most of this is identical to, uhm, OAC, the artifact system is similar, uhm, when you're actually like working on editing, you're gonna work with a PixFlake that set up similar
00:26 pre-commit hooks or similar labels are generated a similar way. You can find information about the issues, uhm, from the same table, with the same labels, with the same relationship between release candidates and events.
00:41 So if you've somehow hopped here, uhm, do go and check out that OAC repo, that's where all this. began, uh, and watch the demo that I will link in association with this video, uh, to get a sense and then come back here.
00:57 Uhm, so let me just briefly show you what each of these things looks like, just to reiterate that point. But, uhm, if you come into the repository you're going to see artifacts.
01:11 These artifacts are what you're going to work on editing for the most part. Uhm, plans around how you are going to make changes to those artifacts, general tasking, uhm, are going to come down from events.
01:27 See, we have this Hello World, uh, week zero readiness event, which, uh, right Now I'm linking to the OAC repo, this will be a short change to the remain repo, but it's the same thing.
01:39 You just explore these guys. Uhm, and, uhm, the only thing I want to expand upon in this video, actually let me show you guys the terminal first.
01:59 If you, Nix development. Up, you'll see you get like a different logo and roommate and all that stuff. And go in, uhm, like I said, you'll see the same pre-commit hooks, uhm, for different, but it's the same hook that manages it.
02:18 And there's also the same labels, workflow and all that jazz. So it's, it's very, very similar setup. Uh, now the only thing I'm going to talk about that's going to be new information is a bit more about the use of projects throughout the roommate organization.
02:36 And then, uh, also, uhm, you know, what exists in this repo versus what would be in OAC at the end.
02:48 Okay, so let's talk about projects. Uhm, from that OAC demo video, you would have seen this task board, uhm, for the hello world week zero readiness project.
03:08 So, I've dragged over produce RDemo0. It's in progress because I'm working on it as I'm recording this video, uhm, and it should be marked, I actually forgot to do this, it should be marked in progress for all associated projects.
03:25 So, that, that much is all the same, but in commenting, or to comment on the use of projects for the roommate I.O.
03:36 organization. Uhm, the general rule of thumb is going to be that each repository gets its own project, so like the roommate repository gets its own project, uhm, and that each event gets its own project.
03:56 This is so that we can look at more and less granular task boards. Uhm, now, some of these repositories are going to be, you know, more organizational and tie into lots of different things, so like, roommate, uh, issues that are tagged for roommate, uh, would include things that are tagged for like the
04:22 Roblaze project and similarly for OAC. Uhm, and then also, there are going to be like actual child repositories, uhm, and whatnot that show up, like Roblaze has essentially direct parent-child relationships with the stack repositories with GuardFile, FOS, CircuVay, and GA.
04:49 So, uhm, for those, you should also see that, like, double-tagging going on, and multi-tagging. Uhm, essentially, the use of projects is just to have these tags everywhere, so that when we're doing lots of things across repositories, to get something out the door, uhm, or to like contribute in a particular
05:13 way. Conceptual Venn, it's, it's available from multiple viewpoints, from potentially multiple different groups of people coming in and looking at this.
05:23 Or, just you looking at it in a few different ways, what you're trying to get done. Uhm, okay, so that's projects.
05:32 Uhm. Essentially, the bottom line is just remember to tag with relevant projects. Don't worry about overtagging.
05:45 Let's, let's go to Remate, uh, the Remate repository real quick. So I can spend a moment kind of waxing about what's going on in the Remate repository versus OAC.
05:58 it. So, we're made. Is the repository where the artifacts are concerned with essentially the org, the LLC that I have Remate, uh.
06:12 So these are going to differ from OAC in the sense that they're not going to be like so conceptually geared and geared towards that particular technology.
06:24 They're going to be. Geared towards defining things which can be used across multiple projects over time, are concerned with the org maintaining itself, are concerned with governance of the org on the whole, are concerned with applications that we're trying to push out, uhm, whereas OAC is going to be
06:44 concerned with kind of the next step and improvement in, uh, the concepts available. Uhm, and then what I intend to have happen is for larger projects which are, you know, not conceptual so much, like, are implementation specific and are applications that we're trying to guide, I intend to have those
07:10 have their own governance. So, like, Roblox. is an example of that. So how does this look for, like, something practical?
07:18 Well, I would expect, uhm, let's say we're trying to specify, uh, like, a virtual machine adapter, uh, that is correct with respect to BFA.
07:34 Uh, and we're going to try to take that all the way through Thank the entire org, right? Okay, so I would expect the, uhm, conceptual artifacts for this are going to land in OAC, uhm, that you're going to have some, like, relatively generalized and well formalized.
08:01 specification for, uh, a virtual machine that works in the appropriate way with BFA protocols under some assumptions. Uhm, and you'll write that up and then, uh, you know, roommates might have some comments.
08:25 on that, uh, concept in here and how it applies to a particular business roadmap. And so there might be, you know, a line item in, in our road artifact.
08:39 And then Robles would be the place I would expect a full specification of how to integrate that into a particular I'll see a layer.
08:52 I first, um, would take place. So then you would end up with a row spec here, right? So you, in overall, you might have for this VM adapter, you might have an O spec.
09:09 That's kind of the highest conceptual source of truth. You might have a line item and an R road that specifies how this is, uhm, potentially relevant to business goals.
09:29 And then you might have the full specification for actual implementation and I'll see a row spec, uhm, which is what developers should be looking at to put this together.
09:44 Okay, so that's, that's how these repositories which are similar in structure differ semantically and how they all come together. Hopefully that provides some initial motivation.
09:59 Uhm, and hopefully this will this video on the whole gives a sense of how to use Remate and what you should do with it.
<!-- vale on -->
<!-- ltex: enabled=true -->

<!--RAMATE FOOTER: DO NOT REMOVE THIS LINE-->
---

<div align="center">
  <a href="https://github.com/ramate-io/oac">
    <picture>
      <source srcset="/assets/ramate-inverted-transparent.png" media="(prefers-color-scheme: dark)">
      <img height="24" src="/assets/ramate-transparent.png" alt="Ramate"/>
    </picture>
  </a>
  <br/>
  <sub>
    <b>Ramate</b>
    <br/>
    &copy; 2025 <a href="https://github.com/ramate-io/ramate">ramate-io/ramate</a>
    <br/>
    <a href="https://github.com/ramate-io/ramate/blob/main/LICENSE">MIT License</a>
    <br/>
    <a href="https://www.ramate.io">ramate.io</a>
  </sub>
</div>
