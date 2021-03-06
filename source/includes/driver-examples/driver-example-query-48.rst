.. tabs-drivers::

   tabs:
     - id: shell
       content: |
         .. class:: copyable-code
         .. code-block:: javascript

            db.inventory.find(
               { status: "A" },
               { "size.uom": 0 }
            )

     - id: compass
       content: |
         Copy the following expression into the :guilabel:`Filter` bar:

         .. class:: copyable-code
         .. code-block:: javascript

            { status: "A" }

         Copy the following expression into the :guilabel:`Project`
         bar:

         .. class:: copyable-code
         .. code-block:: javascript

            { "size.uom": 0 }

         Click :guilabel:`Find`.

         .. figure:: /images/compass-project-suppress-embedded-field.png

     - id: python
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/test_examples.py
            :language: python
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: motor
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/test_examples_motor.py
            :language: python
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: java-sync
       content: |
         To specify a projection document, chain the
         com.mongodb.client.FindIterable.projection_ method to the
         ``find`` method. The example uses the
         com.mongodb.client.model.Projections_ class to create the
         projection documents.

         .. class:: copyable-code
         .. literalinclude:: /driver-examples/DocumentationSamples.java
            :language: java
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: java-async
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/AsyncDocumentationSamples.java
            :language: java
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: nodejs
       content: |
         .. literalinclude:: /driver-examples/node_project.js
            :language: javascript
            :dedent: 6
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: php
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/DocumentationExamplesTest.php
            :language: php
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: perl
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/driver-examples.t
            :language: perl
            :dedent: 4
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: ruby
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/shell_examples_spec.rb
            :language: ruby
            :dedent: 8
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: scala
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/DocumentationExampleSpec.scala
            :language: scala
            :dedent: 4
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: csharp
       content: |
         .. class:: copyable-code
         .. literalinclude:: /driver-examples/DocumentationExamples.cs
            :language: c#
            :dedent: 12
            :start-after: Start Example 48
            :end-before: End Example 48

     - id: go
       content: |
         .. literalinclude:: /driver-examples/crud_examples.go
            :language: go
            :dedent: 2
            :start-after: Start Example 48
            :end-before: End Example 48
