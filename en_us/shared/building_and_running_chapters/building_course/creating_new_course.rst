.. _Creating a New Course:

###########################
Creating a Course
###########################

This topic describes how to use Studio to create and set up a course.

.. contents::
  :local:
  :depth: 1

.. only:: Partners

   You can create courses on the edX Edge site only if you have course creation
   permissions. For more information, see :ref:`Use Studio on Edge`. Only edX
   staff members can create courses on edx.org.

Another way to create a course is for a system administrator to re-run an
existing course. For more information, see :ref:`Rerun a Course`.

You can also :ref:`export<Export a Course>` and :ref:`import<Import a Course>`
courses as XML files. You can do this when you need to back up a course or edit
the course in XML.

.. _Identifying the Course:

**************************
Identifying the Course
**************************

Before you create a course, consider the identifying information that you will
provide for it carefully.

* For **Course Name**, you enter the title of your course. For example, the
  name might be "Sets, Maps, and Symmetry Groups". Use title capitalization for
  the course title, and normal spacing and punctuation.

* For **Organization**, you enter the identifier for your organization. Do not
  include spaces or special characters.

* For **Course Number**, you enter both a subject abbreviation and a number.
  For example, for public health course number 207, enter ``PH207``. For math
  course 101x, enter ``Math101x``. Do not include spaces or special characters
  in the course number.

  .. note:: If your course will be public, be sure to include the "x".
      If it is exclusively an on campus offering, do not include the "x".

* For **Course Run**, you enter the term in which your course will run. For
  example, enter 2014SOND or T2_2014. Do not include spaces or special
  characters.

  The value that you enter for the run does not affect the course start date
  that you define for the course. For more information, see :ref:`Scheduling
  Your Course`.

The organization, course number, and course run values that you enter are used
to create the URL for your course. Because URLs do not have an unlimited
length, the total number of characters that you enter for these values must be
65 or fewer.

.. important:: The values that you enter for the organization, course number,
 and course run cannot be edited after you create your course.

.. _Create a New Course:

*******************
Create a Course
*******************

.. only:: Partners

  To create a course on edX Edge, follow these steps.

.. only:: only:: Open_edX

  To create a course, follow these steps.


#. Sign in to Studio.

#. Select **New Course**.

#. Enter the :ref:`identifying course information<Identifying the Course>`, and
   then select **Create**.

  .. image:: ../../../shared/building_and_running_chapters/Images/new_course_info.png
     :width: 600
     :alt: Image of the course creation page in Studio.

#. Select **Save**. The :ref:`Course Outline<Developing Your Course Outline>`
   page opens.

.. _Edit Your Course:

************************
Edit a Course
************************

After you create a course, the course opens in Studio automatically and you can
begin editing. Your next steps might include adding other :ref:`course team
members<Add Course Team Members>`, setting the course :ref:`start and end
dates<Scheduling Your Course>`, or developing the :ref:`course
outline<Developing Your Course Outline>`.

When you return to Studio later, your **My Courses** dashboard page lists
the courses that you created as well as any courses for which you have course
team privileges.

.. image:: ../../../shared/building_and_running_chapters/Images/open_course.png
  :width: 600
  :alt: Image of the course on the Studio dashboard

To edit a course, select the course name. The Studio **Course Outline** page
appears.

.. Topic commented out per M. Rudnick as the course checklist is sending people to info that is not just out of date, it's bad. - Alison 30 Oct 15

.. .. _Use the Course Checklist:

.. ************************
.. Use the Course Checklist
.. ************************

.. You can use a Course Checklist within Studio to help you work through the tasks of building a course.

.. Tasks in the Course Checklist are organized into the following categories.

.. * Getting Started with Studio
.. * Draft a Rough Course Outline
.. * Explore edX's Support Tools
.. * Draft Your Course About Page

.. From the **Tools** menu, select **Checklists**.

.. .. image:: ../../../shared/building_and_running_chapters/Images/checklist.png
  :width: 600
  :alt: Image of the Getting Started with Studio checklist in Studio.

.. As shown in this example for the **Add Course Team Members** task, when you move your cursor over a task, an option appears that you can select to go to the page where you can complete that task.

.. You can expand and collapse the checklist categories as needed.

.. You can check tasks as you complete them. Studio saves your changes automatically. Other members of the course team can see your changes.

.. _Add Course Team Members:

**************************
Addng Course Team Members
**************************

Course team members are users who help you build your course. Before you can
assign the Staff or Admin role to a team member so that they can access your
course in Studio, you must meet these prerequisites.

* You must be an Admin.

* The team member that you want to add must register a user account and
  activate the account.

* You need the same, registered email address for the team member you want to
  add.

The course team members that you add with the Staff role can edit the course
and complete all tasks, except adding and removing other team members.

.. note::  Any course team member can delete content created by other team
 members.

=========================
Add a Course Team Member
=========================

.. important:: Course team members are not automatically enrolled in courses,
   although they can access content in Studio, the LMS, and Insights. To work
   on a course, every course team member must register, activate a user
   account, and enroll in the course.

To add a course team member, follow these steps.

#. Ensure you have Admin access.
#. Ensure that the new team member has registered and activated an account.
#. In Studio, from the **Settings** menu, select **Course Team**.
#. Select **Add a New Team Member**.
#. Enter the new team member's email address, and then select **ADD USER**.

The new team member can now work on the course in Studio.

* To preview the course in the LMS, the team member must enroll in the course.

* To moderate course discussions, the team member must also have one of the
  discussion roles. For more information, see
  :ref:`Assigning_discussion_roles`.

You can also assign these privileged roles to users when you work in the LMS.
For more information about assigning roles while you run your course, see
:ref:`Course_Staffing`.

You can also designate teams of people to beta test your course and to
moderate and manage its discussions by assigning other LMS roles. The beta
testers and discussion administrators must be enrolled in your course, but
they do not need to have Staff or Admin access. For more information, see
:ref:`Beta_Testing` and :ref:`Assigning_discussion_roles`.

.. include:: ../../../links/links.rst
