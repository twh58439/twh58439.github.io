<template>
  <div class="mt-3">
    <h3>Quizzing System: User Stories</h3>
    <p class="font-italic">
      "As a student, I want a quizzing system that makes me feel like I actually
      should be engaged in the course material rather than the traditional
      “attendance polls."
    </p>
    <p class="font-italic">
      "As an instructor, I want a better quizzing system so that I may discern
      the current state of my student’s learning journey, regardless if they’re
      remote or in-person."
    </p>
    <p>
      Quizzes - both formal graded quizzes and question-response actions in the
      instructor are vital to gauging a student's mastery of the material, as
      well as give the instructor feedback on their effectivess. Learning
      platforms like ELC are fine for formal quizzes, but if the instructor
      simply wants to ask a few questions, it is not practical to expect the
      students to switch over, answer a few small questions, then switch back to
      their learning material.
    </p>
    <p>
      Zoom has a "polling" system, but while it allows students to select
      answers, it simply gives the percent-answer spread over the answers and
      not which is correct. It also requires teachers to create polls on the
      fly, and any long-term tracking of quiz performance is lost unless
      manually tracked. We aim to improve the ability for hybrid-synchronous
      students actively engage with the material, while also improving the
      instructors ability to create quizzes and associate them with the
      material.
    </p>
    <h4>Functional Goals</h4>
    <div class="mt-3">
      <ul>
        <li>
          This will involve having preset quizzes for each lecture with good
          video integration for chat and screen share.
        </li>
        <li>
          Instructors will able able to upload presentations during lectures to
          work with the quizzing/discussion system
        </li>
        <li>
          Have built in times assignments to check student understanding during
          lectures, as well as being able to organize the students into sections
          for organizational reasons.
        </li>
      </ul>
    </div>
    <h4>Mockup Progression</h4>
    <b-row>
      <b-col>
        <h6>Gradebook</h6>
        <b-img
          fluid-grow
          src="~/assets/low_fidelity/quiz_gradebook_student_view.png"
        ></b-img>
        <b-img
          fluid-grow
          src="~assets/high_fidelity/quiz_gradebook_student_view.png"
        ></b-img>
      </b-col>
      <b-col>
        <h6>Quiz View</h6>
        <b-img fluid-grow src="~/assets/low_fidelity/quiz_view.png"></b-img>
        <b-img
          class="mt-2"
          fluid-grow
          src="~/assets/high_fidelity/quiz_view.png"
        ></b-img>
      </b-col>
    </b-row>
  </div>
</template>
