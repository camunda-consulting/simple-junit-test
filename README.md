# simple-junit-test

This project is a template to test processes with [camunda-bpm-assert](https://github.com/camunda/camunda-bpm-assert) and [process test coverage](https://github.com/camunda/camunda-process-test-coverage) with JUnit.

Just copy the project to your disk, copy your process into `src/main/resources`, complete the `InMemoryH2Test.java` and run it with `mvn clean test`.

You can inspect the process test coverage unter `target/process-test-coverage` by opening the files in your browser.
