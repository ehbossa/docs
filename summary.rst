Summary
==========

.. _summary:

:dfn:`Open Data Kit` (ODK) is a suite of open source tools for collecting and managing survey data using mobile forms. Below is a summary of the key components and their roles.

Data Collection
-----------------

- :doc:`ODK Collect <collect-guide>` — An Android app that replaces paper forms for survey-based data gathering. Collect can get blank forms from an Aggregate server, fill them out with participants, and upload completed surveys.

- :doc:`ODK Aggregate <aggregate-guide>` — A server that stores, manages, and visualizes collected data. Aggregate provides blank forms to Collect, accepts finalized submissions, and can export data as CSV or KML files.

- :doc:`ODK Briefcase <briefcase-guide>` — A Java application for fetching and pushing forms and data between Collect and Aggregate, useful when there is no internet connectivity.

Form Building
---------------

- :doc:`ODK Build <odk-build>` — A drag-and-drop form designer available online or as a desktop application.

- :doc:`ODK XLSForm <xlsform>` — A tool for designing forms in Excel using a simple spreadsheet format.

- :doc:`ODK Validate <validate>` — Validates forms against the ODK XForms specification.

- :doc:`Form Uploader <form-uploader>` — Uploads blank forms and their media files to an Aggregate server.

Specifications and Libraries
-------------------------------

- :doc:`ODK XForm (OpenRosa) <openrosa>` — A subset of the W3C XForms specification used across the ODK ecosystem.

- :doc:`ODK JavaRosa <javarosa>` — A Java library that renders ODK XForm-compliant forms.

Getting Started
-----------------

For a step-by-step walkthrough, see the :doc:`Getting Started Guide <getting-started>`.

For security and privacy information, see :doc:`security-privacy`.
