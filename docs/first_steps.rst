First Steps
===========

.. currentmodule:: weasyprint


Installation
------------

WeasyPrint |version| depends on:

* Python_ ≥ 3.9.0
* Pango_ ≥ 1.44.0
* pydyf_ ≥ 0.10.0
* CFFI_ ≥ 0.6
* tinyhtml5_ ≥ 2.0.0b1
* tinycss2_ ≥ 1.3.0
* cssselect2_ ≥ 0.8.0
* Pyphen_ ≥ 0.9.1
* Pillow_ ≥ 9.1.0
* fontTools_ ≥ 4.0.0

.. _Python: https://www.python.org/
.. _Pango: https://pango.gnome.org/
.. _CFFI: https://cffi.readthedocs.io/
.. _pydyf: https://doc.courtbouillon.org/pydyf/
.. _tinyhtml5: https://doc.courtbouillon.org/tinyhtml5/
.. _tinycss2: https://doc.courtbouillon.org/tinycss2/
.. _cssselect2: https://doc.courtbouillon.org/cssselect2/
.. _Pyphen: https://pyphen.org/
.. _Pillow: https://python-pillow.org/
.. _fontTools: https://github.com/fonttools/fonttools

There are many ways to install WeasyPrint, depending on the system you use.


Linux
~~~~~

The easiest way to install WeasyPrint on Linux is to use the package manager of
your distribution. WeasyPrint is packaged for recent versions of Debian_,
Ubuntu_, Fedora_, Archlinux_, Gentoo_…

.. _Debian: https://packages.debian.org/search?keywords=weasyprint&searchon=names&suite=all&section=all
.. _Ubuntu: https://packages.ubuntu.com/search?keywords=weasyprint&searchon=names&suite=all&section=all
.. _Fedora: https://src.fedoraproject.org/rpms/weasyprint
.. _Archlinux: https://aur.archlinux.org/packages/python-weasyprint
.. _Gentoo: https://packages.gentoo.org/packages/dev-python/weasyprint

If WeasyPrint is not available on your distribution, or if you want to use a
more recent version of WeasyPrint, you have to be sure that Python_ and Pango_
are installed on your system, and that they are recent enough. You can verify
this by launching::

  python3 --version
  pango-view --version

If the version of Pango provided by your distribution is too old, you can use
version 52.5 of WeasyPrint which does not need recent Pango features.

When everything is OK, you can install WeasyPrint directly on your system or
in a `virtual environment`_ using `pip`_::

  python3 -m venv venv
  source venv/bin/activate
  pip install weasyprint
  weasyprint --info

.. _virtual environment: https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
.. _pip: https://pip.pypa.io/


Alpine ≥ 3.17
+++++++++++++

To install WeasyPrint using your distribution’s package::

  apk add weasyprint

To install WeasyPrint inside a virtualenv using wheels (if possible), you need
the following packages::

  apk add py3-pip so:libgobject-2.0.so.0 so:libpango-1.0.so.0 so:libharfbuzz.so.0 so:libharfbuzz-subset.so.0 so:libfontconfig.so.1 so:libpangoft2-1.0.so.0

To install WeasyPrint inside a virtualenv without using wheels, you need the
following packages::

  apk add py3-pip so:libgobject-2.0.so.0 so:libpango-1.0.so.0 so:libharfbuzz.so.0 so:libharfbuzz-subset.so.0 so:libfontconfig.so.1 so:libpangoft2-1.0.so.0
  apk add gcc musl-dev python3-dev zlib-dev jpeg-dev openjpeg-dev libwebp-dev g++ libffi-dev


Archlinux
+++++++++

To install WeasyPrint using your distribution’s package::

  pacman -S python-weasyprint

To install WeasyPrint inside a virtualenv using wheels (if possible), you need
the following packages::

  pacman -S python-pip pango

To install WeasyPrint inside a virtualenv without using wheels, you need the
following packages::

  pacman -S python-pip pango gcc libjpeg-turbo openjpeg2


Debian ≥ 11
+++++++++++

To install WeasyPrint using your distribution’s package::

  apt install weasyprint

To install WeasyPrint inside a virtualenv using wheels (if possible), you need
the following packages::

  apt install python3-pip libpango-1.0-0 libpangoft2-1.0-0 libharfbuzz-subset0

To install WeasyPrint inside a virtualenv without using wheels, you need the
following packages::

  apt install python3-pip libpango-1.0-0 libpangoft2-1.0-0 libharfbuzz-subset0 libjpeg-dev libopenjp2-7-dev libffi-dev


Fedora ≥ 39
+++++++++++

To install WeasyPrint using your distribution’s package::

  dnf install weasyprint

To install WeasyPrint inside a virtualenv using wheels (if possible), you need
the following packages::

  dnf install python-pip pango

To install WeasyPrint inside a virtualenv without using wheels, you need the
following packages::

  dnf install python3-pip pango gcc python3-devel gcc-c++ zlib-devel libjpeg-devel openjpeg2-devel libffi-devel


Ubuntu ≥ 20.04
++++++++++++++

To install WeasyPrint using your distribution’s package::

  apt install weasyprint

To install WeasyPrint inside a virtualenv using wheels (if possible), you need
the following packages::

  apt install python3-pip libpango-1.0-0 libharfbuzz0b libpangoft2-1.0-0 libharfbuzz-subset0

To install WeasyPrint inside a virtualenv without using wheels, you need the
following packages::

  apt install python3-pip libpango-1.0-0 libharfbuzz0b libpangoft2-1.0-0 libharfbuzz-subset0 libffi-dev libjpeg-dev libopenjp2-7-dev


macOS
~~~~~

The easiest way to install WeasyPrint on macOS is to use Homebrew_::

  brew install weasyprint

.. _Homebrew: https://brew.sh/


Windows
~~~~~~~

To use WeasyPrint on Windows, the easiest way is to use the `executable`_ of
the latest release.

.. warning::

   WeasyPrint is regularly marked as malware by different antivirus companies.
   See `#2081`_ or `#2092`_ to get more information on this topic. Don’t
   hesitate to report the false positive detection to your antivirus company in
   order to improve malware detection for future versions.

If you want to use WeasyPrint as a Python library, you’ll have to follow a few
extra steps. Please read this chapter carefully.

The first step is to install the latest version of Python from the `Microsoft
Store`_.

When Python is installed, you have to install Pango and its dependencies. The
easiest way to install these libraries is to use MSYS2. Here are the steps you
have to follow:

- Install `MSYS2`_ keeping the default options.
- After installation, in MSYS2’s shell, execute ``pacman -S mingw-w64-x86_64-pango``.
- Close MSYS2’s shell.

You can then launch a Windows command prompt by clicking on the Start menu,
typing ``cmd`` and clicking the "Command Prompt" icon. Install WeasyPrint in a
`virtual environment`_ using `pip`_::

  python3 -m venv venv
  venv\Scripts\activate.bat
  python3 -m pip install weasyprint
  python3 -m weasyprint --info

.. _executable: https://github.com/Kozea/WeasyPrint/releases
.. _#2081: https://github.com/Kozea/WeasyPrint/issues/2081
.. _#2092: https://github.com/Kozea/WeasyPrint/issues/2092
.. _Microsoft Store: https://apps.microsoft.com/store/search/python
.. _MSYS2: https://www.msys2.org/#installation


Other Solutions
~~~~~~~~~~~~~~~

Other solutions are available to install WeasyPrint. These solutions are not
tested but they are known to work for some use cases on specific platforms.

Macports
++++++++

On macOS, you can install WeasyPrint’s dependencies with Macports_::

  sudo port install py-pip pango libffi

You can then install WeasyPrint in a `virtual environment`_ using `pip`_::

  python3 -m venv venv
  source venv/bin/activate
  pip install weasyprint
  weasyprint --info

.. _Macports: https://www.macports.org/

Conda
+++++

On Linux and macOS, WeasyPrint is available on Conda_, with `a WeasyPrint
package on Conda Forge`_.

.. _Conda: https://docs.conda.io/projects/conda/en/latest/
.. _a WeasyPrint package on Conda Forge: https://anaconda.org/conda-forge/weasyprint

WSL
+++

On Windows, you can also use WSL_ and install WeasyPrint the same way it has to
be installed on Linux.

.. _WSL: https://docs.microsoft.com/en-us/windows/wsl/

.NET Wrapper
++++++++++++

On Windows, Bader Albarrak maintains `a .NET wrapper`_.

.. _a .NET wrapper: https://github.com/balbarak/WeasyPrint-netcore

AWS
+++

Kotify maintains `an AWS Lambda layer`_, see issue `#1003`_ for more
information.

.. _an AWS Lambda layer: https://github.com/kotify/cloud-print-utils
.. _#1003: https://github.com/Kozea/WeasyPrint/issues/1003

Docker
++++++

Luca Vercelli maintains `Docker images`_.

.. _an AWS Lambda layer: https://github.com/kotify/cloud-print-utils
.. _Docker images: https://github.com/luca-vercelli/WeasyPrint-docker-images/


Troubleshooting
~~~~~~~~~~~~~~~

Most of the installation problems have already been met, and some `issues on
GitHub`_ could help you to solve them. If the solutions here don’t solve your
problem, please open a new issue (and don’t add comments to closed issues).

.. _issues on GitHub: https://github.com/Kozea/WeasyPrint/issues

Missing Library
+++++++++++++++

On Windows or macOS, most of the problems come from unreachable libraries. If
you get an error like ``cannot load library 'xxx': error xxx``, it means that
WeasyPrint can’t find this library.

On Windows, you can set the ``WEASYPRINT_DLL_DIRECTORIES`` environment variable
to list the folders where the DLL files can be found. For example, in
``cmd.exe``::

  set WEASYPRINT_DLL_DIRECTORIES=C:\msys64\mingw64\bin

On macOS, you can set the ``DYLD_FALLBACK_LIBRARY_PATH`` environment variable::

  export DYLD_FALLBACK_LIBRARY_PATH=/opt/homebrew/lib:$DYLD_FALLBACK_LIBRARY_PATH

Of course, check that the folders you set actually contain the ``.dll`` (on
Windows) or ``.dylib`` (on macOS) files WeasyPrint requires.

Missing Fonts
+++++++++++++

If no character is drawn in the generated PDF, or if you get squares instead of
letters, you have to install fonts and make them available to WeasyPrint.
Following the standard way to install fonts on your system should be enough.
You can also use ``@font-face`` rules to explicitly reference fonts using URLs.


Command-Line
------------

Using the WeasyPrint command line interface can be as simple as this:

.. code-block:: sh

    weasyprint https://weasyprint.org /tmp/weasyprint-website.pdf

You may see warnings on the standard error output about unsupported CSS
properties. See :ref:`Command-Line API` for the details of all available
options.

In particular, the ``-s`` option can add a filename for a
:ref:`user stylesheet <Stylesheet Origins>`. For quick experimentation
however, you may not want to create a file. In bash or zsh, you can
use the shell’s redirection instead:

.. code-block:: sh

    weasyprint https://weasyprint.org /tmp/weasyprint-website.pdf \
        -s <(echo 'body { font-family: serif !important }')

If you have many documents to convert you may prefer using the Python API
in long-lived processes to avoid paying the start-up costs every time.


Python Library
--------------

.. attention::

    Using WeasyPrint with untrusted HTML or untrusted CSS may lead to various
    :ref:`security problems <security>`.

Quickstart
~~~~~~~~~~

The Python version of the above example goes like this:

.. code-block:: python

    from weasyprint import HTML
    HTML('https://weasyprint.org/').write_pdf('/tmp/weasyprint-website.pdf')

… or with the inline stylesheet:

.. code-block:: python

    from weasyprint import HTML, CSS
    HTML('https://weasyprint.org/').write_pdf('/tmp/weasyprint-website.pdf',
        stylesheets=[CSS(string='body { font-family: serif !important }')])

Instantiating HTML and CSS Objects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have a file name, an absolute URL or a readable :term:`file object`,
you can just pass it to :class:`HTML` or :class:`CSS` to create an instance.
Alternatively, use a named argument so that no guessing is involved:

.. code-block:: python

    from weasyprint import HTML

    HTML('../foo.html')  # Same as …
    HTML(filename='../foo.html')

    HTML('https://weasyprint.org')  # Same as …
    HTML(url='https://weasyprint.org')

    HTML(sys.stdin)  # Same as …
    HTML(file_obj=sys.stdin)

If you have a byte string or Unicode string already in memory you can also pass
that, although the argument must be named:

.. code-block:: python

    from weasyprint import HTML, CSS

    # HTML('<h1>foo') would be filename
    HTML(string='''
        <h1>The title</h1>
        <p>Content goes here
    ''')
    CSS(string='@page { size: A3; margin: 1cm }')

If you have ``@font-face`` rules in your CSS, you have to create a
``FontConfiguration`` object:

.. code-block:: python

    from weasyprint import HTML, CSS
    from weasyprint.text.fonts import FontConfiguration

    font_config = FontConfiguration()
    html = HTML(string='<h1>The title</h1>')
    css = CSS(string='''
        @font-face {
            font-family: Gentium;
            src: url(https://example.com/fonts/Gentium.otf);
        }
        h1 { font-family: Gentium }''', font_config=font_config)
    html.write_pdf(
        '/tmp/example.pdf', stylesheets=[css],
        font_config=font_config)

Rendering to a Single File
~~~~~~~~~~~~~~~~~~~~~~~~~~

Once you have a :class:`HTML` object, call its :meth:`HTML.write_pdf` method to
get the rendered document in a single PDF file.

Without arguments, this method returns a byte string in memory. If you pass a
file name or a writable :term:`file object`, they will write there directly
instead. (**Warning**: with a filename, these methods will overwrite existing
files silently.)

Rendering Individual Pages
~~~~~~~~~~~~~~~~~~~~~~~~~~

If you want more than a single PDF, the :meth:`HTML.render` method gives you a
:class:`document.Document` object with access to individual
:class:`document.Page` objects. Thus you can get the number of pages, their
size\ [#]_, the details of hyperlinks and bookmarks, etc. Documents also have a
:meth:`document.Document.write_pdf` method, and you can get a subset of the
pages with :meth:`document.Document.copy()`.

.. [#] Pages in the same document do not always have the same size.

See the :ref:`Python API` for details. A few random examples:

.. code-block:: python

    # Write odd and even pages separately:
    #   Lists count from 0 but page numbers usually from 1
    #   [::2] is a slice of even list indexes but odd-numbered pages.
    document.copy(document.pages[::2]).write_pdf('odd_pages.pdf')
    document.copy(document.pages[1::2]).write_pdf('even_pages.pdf')

.. code-block:: python

    # Print the outline of the document.
    # Output on https://www.w3.org/TR/CSS21/intro.html
    #     1. Introduction to CSS 2.1 (page 2)
    #       1. A brief CSS 2.1 tutorial for HTML (page 2)
    #       2. A brief CSS 2.1 tutorial for XML (page 5)
    #       3. The CSS 2.1 processing model (page 6)
    #         1. The canvas (page 7)
    #         2. CSS 2.1 addressing model (page 7)
    #       4. CSS design principles (page 8)
    def print_outline(bookmarks, indent=0):
        for i, bookmark in enumerate(bookmarks, 1):
            page = bookmark.destination[0]
            print('%s%d. %s (page %d)' % (
                ' ' * indent, i, bookmark.label.lstrip('0123456789. '), page))
            print_outline(bookmark.children, indent + 2)
    print_outline(document.make_bookmark_tree())

URL Fetchers
~~~~~~~~~~~~

WeasyPrint goes through a *URL fetcher* to fetch external resources such as
images or CSS stylesheets. The default fetcher can natively open file and
HTTP URLs, but the HTTP client does not support advanced features like cookies
or authentication. This can be worked-around by passing a custom
``url_fetcher`` callable to the :class:`HTML` or :class:`CSS` classes.
It must have the same signature as :func:`default_url_fetcher`.

Custom fetchers can choose to handle some URLs and defer others
to the default fetcher:

.. code-block:: python

    from weasyprint import default_url_fetcher, HTML

    def my_fetcher(url):
        if url.startswith('graph:'):
            graph_data = map(float, url[6:].split(','))
            string = generate_graph(graph_data)
            return {'string': string, 'mime_type': 'image/png'}
        return default_url_fetcher(url)

    source = '<img src="graph:42,10.3,87">'
    HTML(string=source, url_fetcher=my_fetcher).write_pdf('out.pdf')

Flask-WeasyPrint_ for Flask_ and Django-Weasyprint_ for Django_ both make
use of a custom URL fetcher to integrate WeasyPrint and use the filesystem
instead of a network call for static and media files.

A custom fetcher should be returning a :obj:`dict` with

* One of ``string`` (a :obj:`bytestring <bytes>`) or ``file_obj`` (a
  :term:`file object`).
* Optionally: ``mime_type``, a MIME type extracted e.g. from a *Content-Type*
  header. If not provided, the type is guessed from the file extension in the
  URL.
* Optionally: ``encoding``, a character encoding extracted e.g. from a
  *charset* parameter in a *Content-Type* header
* Optionally: ``redirected_url``, the actual URL of the resource if there were
  e.g. HTTP redirects.
* Optionally: ``filename``, the filename of the resource. Usually derived from
  the *filename* parameter in a *Content-Disposition* header

If a ``file_obj`` is given, the resource will be closed automatically by
the function internally used by WeasyPrint to retrieve data.

.. _Flask-Weasyprint: https://github.com/Kozea/Flask-WeasyPrint
.. _Flask: https://flask.pocoo.org/
.. _Django-WeasyPrint: https://github.com/fdemmer/django-weasyprint
.. _Django: https://www.djangoproject.com/


Security
--------

*This section has been added thanks to the very useful reports and advice from
Raz Becker.*

When used with untrusted HTML or untrusted CSS, WeasyPrint can meet security
problems. You will need extra configuration in your Python application to avoid
high memory use, endless renderings or local files leaks.

As for any service dealing with untrusted data, you should at least follow
basic security rules with WeasyPrint: don’t launch the service as root, launch
it as a user with limited access to filesystem, network and memory. Using a
container can also be a simple way to limit the possibilities given to an
attacker in case of security breach.

Long Renderings
~~~~~~~~~~~~~~~

WeasyPrint is pretty slow and can take a long time to render long documents or
specially crafted HTML pages.

When WeasyPrint used on a server with HTML or CSS files from untrusted sources,
this problem can lead to very long time renderings, with processes with high
CPU and memory use. Even small documents may lead to really long rendering
times, restricting HTML document size is not enough.

If you use WeasyPrint on a server with HTML or CSS samples coming from
untrusted users, you should:

- limit rendering time and memory use of your process, for example using
  ``evil-reload-on-as`` and ``harakiri`` options if you use uWSGI,
- limit memory use at the OS level, for example with ``ulimit`` on Linux,
- automatically kill the process when it uses too much memory or when the
  rendering time is too high, by regularly launching a script to do so if no
  better option is available,
- truncate and sanitize HTML and CSS input to avoid very long documents and
  access to external URLs.

Infinite Requests
~~~~~~~~~~~~~~~~~

WeasyPrint can reach files on the network, for example using ``https://``
URIs. For various reasons, HTTP requests may take a long time and lead to
problems similar to :ref:`Long Renderings`.

WeasyPrint has a default timeout of 10 seconds for HTTP, HTTPS and FTP
resources. This timeout has no effect with other protocols, including access to
``file://`` URIs.

If you use WeasyPrint on a server with HTML or CSS samples coming from
untrusted users, or need to reach network resources, you should:

- use a custom :ref:`URL fetcher <URL Fetchers>`,
- follow solutions listed in :ref:`Long Renderings`.

Infinite Loops
~~~~~~~~~~~~~~

WeasyPrint has been hit by a large number of bugs, including infinite
loops. Specially crafted HTML and CSS files can quite easily lead to infinite
loops and infinite rendering times.

If you use WeasyPrint on a server with HTML or CSS samples coming from
untrusted users, you should:

- follow solutions listed in :ref:`Long Renderings`.

Huge Values
~~~~~~~~~~~

WeasyPrint doesn't restrict integer and float values used in CSS. Using huge
values for some properties (page sizes, font sizes, block sizes) can lead to
various problems, including infinite rendering times, huge PDF files, high
memory use and crashes.

This problem is really hard to avoid. Even parsing CSS stylesheets and
searching for huge values is not enough, as it is quite easy to trick CSS
pre-processors using relative units (``em`` and ``%`` for example).

If you use WeasyPrint on a server with HTML or CSS samples coming from
untrusted users, you should:

- follow solutions listed in :ref:`Long Renderings`.

Access to Local Files
~~~~~~~~~~~~~~~~~~~~~

As any web renderer, WeasyPrint can reach files on the local filesystem using
``file://`` URIs. These files can be shown in ``img`` or ``embed`` tags for
example.

When WeasyPrint used on a server with HTML or CSS files from untrusted sources,
this feature may be used to know if files are present on the server filesystem,
and to embed them in generated documents.

Unix-like systems also have special local files with infinite size, like
``/dev/urandom``. Referencing these files in HTML or CSS files obviously lead
to infinite time renderings.

If you use WeasyPrint on a server with HTML or CSS samples coming from
untrusted users, you should:

- restrict your process access to trusted files using sandboxing solutions,
- use a custom :ref:`URL fetcher <URL Fetchers>` that doesn't allow ``file://``
  URLs or filters access depending on given paths.
- follow solutions listed in :ref:`Long Renderings`.

System Information Leaks
~~~~~~~~~~~~~~~~~~~~~~~~

WeasyPrint relies on many libraries that can leak hardware and software
information. Even when this information looks useless, it can be used by
attackers to exploit other security breaches.

Leaks can include (but are not restricted to):

- locally installed fonts (using ``font-family`` and ``@font-face``),
- network configuration (IPv4 and IPv6 support, IP addressing, firewall
  configuration, using ``https://`` URIs and tracking time used to render
  documents),
- Python, Pango and other libraries versions (implementation details
  lead to different renderings).

SVG Images
~~~~~~~~~~

Rendering SVG images more or less suffers from the same problems as the ones
listed here for WeasyPrint.

Security advices apply for untrusted SVG files as they apply for untrusted HTML
and CSS documents.

Note that WeasyPrint’s URL fetcher is used to render SVG files.
