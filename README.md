# docview
This sample show document/view support in wxWidgets.

    It can be run in several ways:
        * With "--mdi" command line option to use multiple MDI child frames
          for the multiple documents (this is the default).
        * With "--sdi" command line option to use multiple top level windows
          for the multiple documents
        * With "--single" command line option to support opening a single
          document only

    Notice that doing it like this somewhat complicates the code, you could
    make things much simpler in your own programs by using either
    wxDocParentFrame or wxDocMDIParentFrame unconditionally (and never using
    the single mode) instead of supporting all of them as this sample does.
