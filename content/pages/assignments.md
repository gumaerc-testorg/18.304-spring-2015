---
content_type: page
description: This section provides descriptions of the course assignments, including
  student presentations, short papers, and the final paper.
learning_resource_types:
- Assignments
ocw_type: CourseSection
title: Assignments
uid: 52ed5162-c38f-fd5d-0dee-3a82287d3342
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Three 35 Minute Lectures
------------------------

*   The first will be given using a slide show, and the second will be a blackboard talk. Students are free to choose either for the third talk.
*   The first and second will be given on a chapter of "_Proofs from THE BOOK_". Students may choose other topics, after coordinating with the instructor.
*   The last lecture will be given on an independently chosen topic.
*   Students are required to give a practice talk, either to a peer or to the instructor (at the instructor's discretion).
*   Students must furthermore prepare a short quiz for the end of their talk, which should take no more than 5 minutes to solve and be easy for anyone who paid attention.

### Guidelines for Giving Lectures

*   Talking about something that you find beautiful and understand well makes it easier to give a good lecture. Make sure you choose topics that you like, and study them well.
*   Find your own style of talking; there is no universal way to give talks.
*   The goal of the lecture is to teach math to your peers. Whatever you do that achieves that goal is good! Not to be confused with
    1.  demonstrating to the instructor that you understand the subject, or
    2.  reading out loud the paper / book chapter that you are presenting.
*   Encourage the audience to ask questions. After explaining a subtle point give them time to think about it before you move on. Maintain eye contact with them to make sure they are still with you.
*   You do not have to prove _everything_ formally, but you should prove _something_ formally and make sure the audience has an idea of how the rest was proved.
*   Talk slowly; the bottleneck of a talk is not how fast you can speak, but how fast the audience can understand. Plan to have some spare time to answer questions, make mistakes etc. This will also help you be more relaxed.
*   Slide shows:
    1.  Don't put more than 4 lines on each slide,
    2.  consider using {{% resource_link "4717a2cb-7f63-4b30-9713-77e81e26c226" "LaTeX _beamer_" %}} rather than WYSIWYG software like PowerPoint (a {{% resource_link 6a63c85a-3066-7dae-3dce-4da66ce13e6a "LaTeX beamer template (TEX)" %}} is available) 
    3.  give the audience time to read each slide, and
    4.  use figures!
*   Also, come 10 minutes before your lecture to make sure your computer connects properly to the projector.

Students are strongly encouraged to meet the instructor while preparing their talks to discuss mathematical content, delivery strategy, or any other issues.

Short Paper
-----------

*   Write a short (2 to 4 page) paper on the topic below. Papers must be written in {{% resource_link "258c2d5f-8d0c-4c08-a809-aee4a711f624" "LaTeX" %}}.
*   Prove the following theorem regarding asynchronous majority dynamics:

**Theorem.** _Let G=(V, E) be a finite, undirected simple graph with odd degrees. Then, for any initial opinions and any update sequence, the size of the set {(u,t) | X{{< sup "u" >}}{{< sub "t" >}}_ __≠_ X{{< sup "u" >}}{{< sub "t-1" >}}} is at most |E|._

*   The synchronous analogue of this theorem appears in "{{% resource_link "efa61a92-6c03-47c2-a56c-74387184c9bf" "Periodic Behaviour of Generalized Threshold Functions" %}}." by E. Goles and J. Olivos, Discrete Mathematics, 1980.
*   Paper outline:
    *   No need to define graphs.
    *   Define majority dynamics (asynchronous).
    *   Define L{{< sub "t" >}}.
    *   Prove the following:
    
    **Lemma.** _L{{< sub "t" >}} is non-increasing_.
    
    *   Prove the theorem.
*   Those who want more of a challenge can prove the following:

**Theorem.** _Let G be a graph of bounded maximal degree, and such that the number of edges at distance r from some vertex w is bounded from above by a polynomial in r. Then there exists a C > 0 such that for any initial opinions and any update sequence, the total number of times that X{{< sup "w" >}}{{< sub "t" >}} ≠ X{{< sup "w" >}}{{< sub "t-1" >}} is at most C._

Very Short Paper
----------------

*   Write a proof of the six color theorem using the {{% resource_link df05e8a0-4440-b08c-af1f-5a887fd2d3e4 "chromatic.tex template (TEX)" %}}. 
*   You can make changes to the template if you wish, but the only requirement is to fill in the proof of the theorem. There's no need to prove the lemma.
*   Hint: Prove by induction on the size on the graph. Another possibility is to assume by contradiction that the theorem is false, and proceed by analyzing a smallest graph that violates it.

Final Paper
-----------

*   Write a final paper on the topic of the last talk. This will include handing in a paper outline, a first draft, a second draft (if necessary) and a final draft. Papers must be written in LaTeX.
*   The paper should be 10 or more pages long, including about 5 or 6 pages of proofs.
*   Papers must be written in {{% resource_link "258c2d5f-8d0c-4c08-a809-aee4a711f624" "LaTeX" %}} and a {{% resource_link 95022bae-41b2-b771-f3cf-8bccd4d275ab "LaTeX template (TEX)" %}} is available. 
*   Don't {{% resource_link "dff0c093-f593-4ff2-b29b-0fa77888e35d" "plagiarize" %}}.