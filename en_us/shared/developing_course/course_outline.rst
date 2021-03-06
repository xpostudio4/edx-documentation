.. _Developing Your Course Outline:

###################################
Developing Your Course Outline
###################################

As you develop your course, you work primarily in the edX Studio course
outline. This section includes the following information about working with
the course outline.

.. contents::
  :local:
  :depth: 1

See the following sections for information about working with the course
building blocks in the course outline.

* :ref:`Developing Course Sections`
* :ref:`Developing Course Subsections`
* :ref:`Developing Course Units`
* :ref:`Developing Course Components`

****************************
Open the Course Outline
****************************

To view the course outline, follow these steps.

#. Log in to edX Studio.
#. In the **My Courses** page, select the course you want to develop.

   The course outline opens by default when you open a course.

When working in a course, to open the outline, from the **Content** menu,
select **Outline**.

The first time you view an outline for a course, it contains no content.

.. image:: ../../../shared/images/outline_empty.png
 :alt: An empty course outline.

You must :ref:`create the first section<Create a Section>`.

********************************************************
Example of a Developed Course in the Outline
********************************************************

The following example shows a sample course in the outline, with indications
for sections, subsections, and units. As you develop your course, it will begin
to look like this example.

.. image:: ../../../shared/images/outline-callouts.png
 :alt: An outline with callouts for sections, subsections, and units.

As this example shows, the course is organized into the following levels.

#. :ref:`Sections<Developing Course Sections>`
#. :ref:`Subsections<Developing Course Subsections>`
#. :ref:`Units<Developing Course Units>`

:ref:`Components<Developing Course Components>` are not shown in the outline. You add or access components by selecting the units that contain them.

Use the links above for more information and instructions on working with each
type of object in the course. The topics in the rest of this section provides
more detail about the course outline.

********************************************************
View the Course Organization as a Learner
********************************************************

The content you see in the outline in Studio is displayed to learners in the
**Courseware** page in the LMS. The following image shows how a learner sees
your course content.

.. image:: ../../../shared/images/Course_Outline_LMS.png
 :alt: Course content from learner's point of view.

.. _Navigating the Course Outline:

*******************************
Navigate the Course Outline
*******************************

In Studio, you navigate the course outline by expanding and collapsing sections
and subsections. Use the "drop-down" icon next to a section or subsection name
to expand or collapse its contents.

.. image:: ../../../shared/images/outline-expand-collapse.png
 :alt: The outline with expand and collapse icons circled.

When you expand a subsection, all units in the subsection are visible.

.. image:: ../../../shared/images/outline-with-units.png
 :alt: The outline with an expanded subsection.

Select the name of a unit to open the :ref:`unit page<Developing Course
Units>`.

.. _Add Content in the Course Outline:

************************************************
Add Content in the Course Outline
************************************************

You add sections, subsections, and units directly in the outline.

* To add a section to the outline, select **New Section**. This option appears
  at both the top of the page and below the current sections in the outline.
  For more information, see :ref:`Create a Section`.

*  To add a subsection to the end of the section, expand the section and select
   **New Subsection**.

   .. image:: ../../../shared/images/outline-new-subsection.png
     :alt: The outline with the New Subsection button circled.

* To add a unit to the end of a subsection, expand the subsection and select
  **New Unit**.

  .. image:: ../../../shared/images/outline-new-unit.png
    :alt: The outline with the New Subsection button circled.

  The :ref:`unit<Developing Course Units>` page opens.

.. the following note is for prerequisite exams, which are currently released in open edx only and not on edx.org.  when they are available on edx.org, this note should no longer be conditionalized.

.. only:: Open_edX

    .. note::
      If you want to require an entrance exam for your course, you also create
      the exam in the course outline. Before you can create an exam, you must
      set your course to require an entrance exam in Studio. For more
      information, see :ref:`Require an Entrance Exam`.

.. _Modify Settings for Objects in the Course Outline:

***************************************************
Modify Settings for Objects in the Course Outline
***************************************************

You modify settings for sections, subsections, and units in the course outline.
Specifically, you can complete the following tasks.

* :ref:`Set a Section Release Date`
* :ref:`Hide a Section from Students`
* :ref:`Set a Subsection Release Date`
* :ref:`Set the Assignment Type and Due Date for a Subsection`
* :ref:`Hide a Subsection from Students`
* :ref:`Hide a Unit from Students`

To modify settings for a section, subsection, or unit, select the **Configure**
icon for that object. In the following example, the **Configure** icon is
circled for a section, a subsection, and two units.

.. image:: ../../../shared/images/settings-icons.png
 :alt: Configure icons in the course outline.

For more information, see the links above.


.. _Publish Content from the Course Outline:

************************************************
Publish Content from the Course Outline
************************************************

You can publish new and changed units for an entire section or subsection. You
can also publish individual units.

To publish new and changed units, select the **Publish** icon for a section,
subsection, or unit. In the following example, the **Publish** icon is circled
for a section, subsection, and unit.

.. image:: ../../../shared/images/outline-publish-icons.png
 :alt: Publishing icons in the course outline.

.. note::
 The **Publish** icon only appears when there is new or changed content within
 the object.

For more information, see the following topics.

* :ref:`Unit Publishing Status`
* :ref:`Publish all Units in a Section`
* :ref:`Publish all Units in a Subsection`
* :ref:`Publish a Unit`

.. _Reorganize the Course Outline:

************************************************
Reorganize the Course Outline
************************************************

You can reorganize your course content by dragging and dropping sections,
subsections, and units to new locations in the outline.

To move a section, subsection, or unit, move your cursor over the handle on the
right of the object's box until the cursor changes to a four-headed arrow. For
example, in the image below, the handle for the subsection Lesson 1 - Getting
Started is selected.

.. image:: ../../../shared/images/outline-drag-select.png
 :alt: A subsection handle selected to drag it.

Then, click and drag the object to the location that you want.

If you expanded the section or subsection you are moving the object to, when
you move the object, a blue line indicates where the object will land when you
release the mouse button. For example, in the image below, the subsection
Lesson 1 - Getting Started is being moved to the end of the section
Introduction.

.. image:: ../../../shared/images/outline-drag-new-location.png
 :alt: A subsection being dragged to a new section.

If you did not expand the section or subsection you are moving the object to,
the outline of that section or subsection turns blue when you have moved the
object to a valid location. You can then release the mouse button. For example,
in the image below, the subsection Lesson 1 - Getting Started is being moved to
the collapsed section Introduction.

.. image:: ../../../shared/images/outline-drag-new-location-collapsed.png
  :alt: A subsection being dragged to a new section.

.. note:: When you move a subsection to a different section, the release date
  and time for that subsection does not change.

.. _Delete Content in the Course Outline:

************************************************
Delete Content in the Course Outline
************************************************

You delete sections, subsections, and units from the course outline.

.. warning::
 You cannot restore course content after you delete it. To ensure you do not
 delete content you may need later, you can move any unused content to a
 section in your course that you set to never release.

Select the **Delete** icon in the box for the object you want to delete.

.. image:: ../../../shared/images/outline-delete.png
 :alt: The outline with Delete icons circled.

You are prompted to confirm the deletion.

.. note::
 When you delete an object, all objects that it contains are deleted. For
 example, when you delete a subsection, all units in that subsection are
 deleted.
