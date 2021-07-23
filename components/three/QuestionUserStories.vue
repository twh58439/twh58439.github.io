<template>
  <div class="mt-3">
    <h3>Question: User Stories</h3>
    <p class="font-italic blockquote-header">
      "As a student, I want to get the attention of my instructor so that I can
      ask a question without significantly interrupting instruction."
    </p>
    <p>
      Communication between students and instructors is a core part of any
      classroom experience, and often serves as an effective generator of
      student-student discussion. Currently, there is a big difference in how
      in-person and remote students simply get the attention of the instructor
      to ask a question or make a comment. Zoom, where much of
      live-communication occurs in a hybrid-synchronous classroom, features
      ineffective tools for virtually raising your hand, and the lack of
      emphasis on the chat feature means the student must hope the instructor
      does not miss their attempt to communicate. For shy students, the thought
      of interrupting the professor might cause them to not speak up despite
      having an urgent question. We aim to improve both the ability for students
      to communicate non-verbaly while still being unobtrusive to the instructor
      or other members of the class, and introduce a new system of asking
      questions that will benefit even those physically in the classroom.
    </p>
    <h4>Functional Goals</h4>
    <b-row class="mt-3">
      <ul>
        <li>
          Provide functionality for overlays for screen shares such as in the
          streaming platform twitch.
        </li>
        <li>
          Have effective nonverbal forms of communication to the instructor such
          as raise hand features.
        </li>
        <li>
          Have reaction like system so instructor can respond to specific
          questions student have posed immediately if necessary.
        </li>
        <li>
          Have a queue-based discussion section for instructor to pull questions
          at end of class, for review purposes or if they could not get to them
          during the lecture.
        </li>
      </ul>
    </b-row>
    <h4>Mockup Progression</h4>
    <h6>Discussion Section</h6>
    <b-row class="mt-3">
      <b-img
        fluid-grow
        src="~assets/low_fidelity/questions_discussion_main.png"
      ></b-img>
      <b-img
        class="mt-2"
        fluid-grow
        src="~assets/high_fidelity/questions_discussion_main.png"
      ></b-img>
      <h6 class="mt-3">Teacher View</h6>
      <b-img
        fluid-grow
        src="~/assets/low_fidelity/questions_teacher_layout.png"
      ></b-img>
      <b-img
        class="mt-2"
        fluid-grow
        src="~/assets/high_fidelity/questions_teacher_layout.png"
      ></b-img>
    </b-row>
  </div>
</template>