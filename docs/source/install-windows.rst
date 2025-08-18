.. _install-windows:

######################
Installation - Windows
######################

This guide provides instructions on installing the Cozmo SDK for computers running with a Windows operating system.

^^^^^^^^^^^^^^^^^^^
Installation Videos
^^^^^^^^^^^^^^^^^^^

For your convenience, videos are provided showing the installation steps being followed on a Windows computer; one using an iOS device, and one using an Android device. There is also full text-based documentation below these.

.. raw:: html

    <video width="690" height="388" controls>
        <source src="/videos/install-windows-ios.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <video width="690" height="388" controls>
        <source src="/videos/install-windows-android.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

|

^^^^^^^^^^^^^^^^^^^
Python Installation
^^^^^^^^^^^^^^^^^^^

Download the `Python 3.5.1 (or later) executable file from Python.org <https://www.python.org/downloads/>`_ and
run it on your computer.

.. important:: We recommend that you tick the "Add Python 3.5 to PATH" checkbox on the Setup screen.

^^^^^^^^^^^^^^^^
SDK Installation
^^^^^^^^^^^^^^^^

To install the SDK, type the following into the Terminal window::

    pip3 install --user Pillow numpy PyOpenGL https://cozmosdk.anki.bot/1.4.12/cozmoclad-3.6.6-py3-none-any.whl https://cozmosdk.anki.bot/1.4.12/cozmo-1.4.12-py3-none-any.whl

"""""""""""
SDK Upgrade
"""""""""""

To upgrade the SDK from a previous install, type the following into the Terminal window::

    pip3 install --user --upgrade Pillow numpy PyOpenGL https://cozmosdk.anki.bot/1.4.12/cozmoclad-3.6.6-py3-none-any.whl https://cozmosdk.anki.bot/1.4.12/cozmo-1.4.12-py3-none-any.whl

^^^^^^^^^^^^^^^^^^^
Mobile Device Setup
^^^^^^^^^^^^^^^^^^^

* **iOS** devices require `iTunes <http://www.apple.com/itunes/download/>`_ to ensure that the usbmuxd service is installed on your computer. Usbmuxd is required for the computer to communicate with the iOS device over a USB cable. While iTunes needs to be installed, it does not need to be running.

* **Android** devices require installation of :ref:`adb` (adb) in order to run the Cozmo SDK. This is required for the computer to communicate with the Android mobile device over a USB cable and runs automatically when required.

^^^^^^^^^^^^^^^
Troubleshooting
^^^^^^^^^^^^^^^

Please see the :ref:`trouble` section of the Initial Setup page for tips, or visit the `Cozmo SDK Forums <https://forums.anki.bot/>`_ to ask questions, find solutions, or for general discussion.

----

`Terms and Conditions <https://anki.bot/policies/terms-of-service>`_ and `Privacy Policy <https://anki.bot/policies/privacy-policy>`_

`Click here to return to the Anki Developer website. <http://developer.anki.bot>`_
