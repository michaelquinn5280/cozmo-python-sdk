.. _install-macos:

###########################
Installation - macOS / OS X
###########################

This guide provides instructions on installing the Cozmo SDK for computers running with a macOS operating system.

^^^^^^^^^^^^^^^^^^^
Installation Videos
^^^^^^^^^^^^^^^^^^^

For your convenience, videos are provided showing the installation steps being followed on a macOS / OS X computer; one using an iOS device, and one using an Android device. There is also full text-based documentation below these.

.. raw:: html

    <video width="690" height="388" controls>
        <source src="/videos/install-macos-ios.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <video width="690" height="388" controls>
        <source src="/videos/install-macos-android.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>  

|

^^^^^^^^^^^^^^^^^^^
Python Installation
^^^^^^^^^^^^^^^^^^^

1. Install `Homebrew <http://brew.sh>`_ on your system according to the latest instructions. If you already had brew installed then update it by opening a Terminal window and typing in the following::

    brew update

2. Once Homebrew is installed and updated, type the following into the Terminal window to install the latest version of Python 3::

    brew install python3

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

* **iOS** devices do not require any special setup in order to run the Cozmo SDK on a macOS system.
* **Android** devices require installation of :ref:`adb` (adb) in order to run the Cozmo SDK. This is required for the computer to communicate with the Android mobile device over a USB cable and runs automatically when required.

^^^^^^^^^^^^^^^
Troubleshooting
^^^^^^^^^^^^^^^

Please see the :ref:`trouble` section of the Initial Setup page for tips, or visit the `Cozmo SDK Forums <https://forums.anki.bot/>`_ to ask questions, find solutions, or for general discussion.

----

`Terms and Conditions <https://anki.bot/policies/terms-of-service>`_ and `Privacy Policy <https://anki.bot/policies/privacy-policy>`_

`Click here to return to the Anki Developer website. <http://developer.anki.bot>`_
