---
title: "Sign Languages"
title_image: /content-images/wai-media-guide/sign.svg
nav_title: "Sign Languages"

lang: en   # change "en" to lang code, here and 2 @@s below
last_updated: 2021-03-08  # Change to date of translation YYYY-MM-DD (month in middle)
# translator: "..."
# contributors: "..."

permalink: /media/av/sign-languages/   # Add lang to end /link/to/page/@@
ref: /media/av/sign-languages/   # Do not change this
layout: default
github:
   repository: w3c/wai-media-guide
   path: 'content/sign-languages.md'   # Add lang to the middle of the filename, e.g., index.@@.md

resource:
  ref: /media/av/
navigation:
  previous: /media/av/transcribing/
  next:     /media/av/player/
changelog: /media/av/changelog/
acknowledgements: /media/av/acknowledgements/

description: Helps you understand and create sign language interpretation for audio and video media accessibility.
image: /content-images/wai-media-guide/social.png

footer: >   # Translate words below, including "Date:" and "Editor:". (Do not update the date.)
   <p><strong>Date:</strong> Updated 8 March 2021. First published September 2019. CHANGELOG.</p>
   <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn">Shawn Lawton Henry</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Originally drafted as part of the <a href="https://www.w3.org/WAI/WCAGTA/">WCAG TA Project</a> funded by the <abbr title="United States">U.S.</abbr> Access Board. Revised as part of the <a href="https://www.w3.org/WAI/expand-access/">WAI Expanding Access project</a> funded by the Ford Foundation.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning. For many people who are Deaf, sign language is their native language, and some do not understand written language well.

This page helps you understand and create sign language interpretation for audio and video. (Sign language is not required by most policies.)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

{% include image.html src="signing-person.jpg" alt="" class="normal right" %}

Sign languages use hand and arm movements, facial expressions, and body positions to convey meaning.

Sign language is the native language of many people who are Deaf. Some do not read or understand written language well &mdash; especially at the speed of most captions.

Some people will want to have sign language and captions at the same time.

Not everyone who is Deaf knows sign language, especially if they became Deaf or hard-of-hearing later in life. Some people use "lip reading" to help understand speech, though that cannot be replied upon for accessibility.

Sign languages are different across regions and countries. For example, American Sign Language (ASL), Black American Sign Language (BASL), British Sign Language (BSL), and Auslan (Australian Sign Language) are different.

There are some efforts to provide automatic sign language from text; however, avatars that simulate sign language interpretation are not robust enough to be adequate.

## Standards Requirements

Sign language is not required in most web accessibility policies.

Sign language is in the WCAG standard at Level AAA: [Understanding 1.2.6 Sign Language](https://www.w3.org/WAI/WCAG21/Understanding/sign-language-prerecorded.html). _(The Planning page of this resource introduces the [WCAG Standard](/media/av/planning/#wcag-standard).)_

## Skills and Tools

To include sign language alternatives, you will need people, skills, and tools to:
* do the sign language interpretation
* record it
* edit it with the audio or video file

## Example

Example sign language in video: [NHS 111 British Sign Language (BSL) Advert (YouTube)<br>{% include image.html src="sign-example.jpg" alt="" class="large video" %}](https://www.youtube.com/watch?v=TCq3ru9HQSc)

## Creating Sign Language Alternatives

Use colors that are easy to distinguish - _planning, recording_
: Usually it is best if the background and the signer’s clothing are solid colors that contrast with their skin tone. That way their hands and face are easier to see.

Use good lighting - _planning, recording_
: Ensure good lighting to help make the signer clearly visible.

Capture the full signing space - _recording_
: For most sign languages the signing space extends from well below the waist to above the head and at least an elbow width to each side.

Ensure the signer is large enough - _post-production_
: Viewers need to be able to clearly see all movements and facial expressions.

Avoid obscuring important content - _post-production_
: Position the signer to avoid obscuring important information in the video. The signer is usually at the bottom right. If your video has information such as a news ticker at the bottom, position the signer above that.
: Ideally when the video was made, the position of the signer was planned for, as noted in another page of this resource: [Plan for sign language – storyboarding, recording](/media/av/av-content/#plan-for-sign-language--storyboarding-recording).

Make sign language video(s) easy to discover and use
: Make it easy to get to the video with sign language and to the video without sign language.
: For example, directly underneath the media player, include a large visible toggle button and/or labelled image for the sign language videos(s).<br><img src="{{ "/content-images/wai-media-guide/sign-button.png" | relative_url }}" alt="" style="max-width: 162px">
{:.paragraph-like}

There are resources on the web that provide additional guidance on creating sign language alternatives. For example:
* [Sign Language Interpretation in HBBTV (PDF){% include_cached external.html %}](http://pagines.uab.cat/hbb4all/sites/pagines.uab.cat.hbb4all/files/sign_language_interpreting_in_hbbtv.pdf) includes specific guidance on aspects such as working with sign language interpreters and types of onscreen presentation
* Guidelines for the Production of Signing Books includes [Sign language presentation {% include_cached external.html %}](http://www.sign-lang.uni-hamburg.de/signingbooks/deliver/d31/deliv_31_part3-2.html#3.2.2.6) and [Editing {% include_cached external.html %}](http://www.sign-lang.uni-hamburg.de/signingbooks/sbrc/grid/d71/guide13.htm)
