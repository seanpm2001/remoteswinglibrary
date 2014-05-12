RemoteSwingLibrary
==================

`Robot Framework`_ library for connecting to a java process and using `SwingLibrary`_.

.. _Robot Framework: http://robotframework.org
.. _SwingLibrary: https://github.com/robotframework/SwingLibrary

Installation
------------

* Download latest RemoteSwingLibrary and documentation from https://github.com/robotframework/remoteswinglibrary/releases/tag/1.1.1
* Add downloaded jar to PYTHONPATH
* After that, you can import the library in your test cases:
    ```
    *** Settings ***
    Library    RemoteSwingLibrary
    
    *** Test Cases ***
    My Test Case
        Start Application    my_app    java -jar MyDemoApplication.jar
    ```
