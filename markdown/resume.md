Vincent Michel
==============

----

>  Software engineer, Python enthusiast and Free Software maintainer

----

Education
---------

2008 - 2012
:   **Computer engineering** – Institut National des Sciences Appliquées – Rennes (France)

    *Engineer's degree (master/bachelor equivalent)*

2012 - 2013
:   **Computer Science** – Rochester Institute of Technology – NY (USA)

    *Exchange program during 2 quarters*

    <br/>

Professional Experience
----------------------

2014 - 2017
:   **Software engineer at MAX-IV Synchrotron** – Lund (Sweden)

2017 - 2019
:   **Software engineer at European Synchrotron Radiation Facility** – Grenoble (France)

    Control system software for particle accelerators:

    * **Python** libraries for many kinds of hardware
    * User interfaces (**PyQt** and command line)

    <br/>
    Software production methods and iterative development:

    * Direct interaction with machine operators and scientists
    * Unit testing (**pytest**) and development of [test utilities][2]
    * Automated packaging and deployment with **Conda**, **Docker** and **Ansible**

    <br/>
    Open-source [**Tango**][1] community:

    * Bug reports and forum support for new comers
    * Maintaining of the [**PyTango**][3] library and other [generic tools][4]

    <br/>

2019 - 2025
:   **Software engineer at SCILLE** – Remote work (France)

    Core developer for [**Parsec**][18], a collaborative file-sharing application with end-to-end encryption

    * **Python** backend developement for the parsec server using [**Starlette**][20] and [**FastAPI**][21]
    * **Rust** development of a certificate-based trust chain, using **cryptographic primitives**
    * Implementation of a dedicated file system using [**FUSE**][21] and [**WinFSP**][22]
    * All contributions publicly available in the [project repository][19]

    <br/>

Programming Projects
--------------------

**Asynchronous programming**

  * Maintaining two asyncio-based libraries: [**aioconsole**][7] and [**aiostream**][8]
  * [Pull request][5] to add [*run_coroutine_threadsafe*][6], merged in **cpython**

**Terminal programming**

  * [**gambaterm**][13], a terminal frontend for the gambatte Game Boy Color emulator
  * [**famiterm**][14], a simple NES emulator running in the terminal

**Low-level programming**

  * [**arm-linux-from-scratch**][15], declaring the **ARM Thumb** instruction set in [customasm][17]
  * [**eater6502-uart-edition**][16], writing programs for a 6502 computer in assembly

----

> <vxgmichel@gmail.com> • French\
> GitHub: [vxgmichel][11] • StackOverflow: [Vincent][12]


[1]: http://www.tango-controls.org/
[2]: https://github.com/vxgmichel/pytango-devicetest
[3]: https://github.com/tango-cs/PyTango
[4]: https://github.com/vxgmichel/tango-gateway
[5]: https://github.com/python/asyncio/pull/273
[6]: https://docs.python.org/3/library/asyncio-task.html#asyncio.run_coroutine_threadsafe
[7]: https://github.com/vxgmichel/aioconsole
[8]: https://github.com/vxgmichel/aiostream
[9]: https://projecteuler.net
[10]: https://code.google.com/codejam/
[11]: https://github.com/vxgmichel/
[12]: http://stackoverflow.com/users/2846140/vincent
[13]: https://github.com/vxgmichel/gambatte-terminal
[14]: https://github.com/vxgmichel/famiterm
[15]: https://github.com/vxgmichel/arm-linux-from-scratch
[16]: https://github.com/vxgmichel/eater6502-uart-edition
[17]: https://github.com/hlorenzi/customasm
[18]: https://parsec.cloud/
[19]: https://github.com/Scille/parsec-cloud
[20]: https://www.starlette.io/
[21]: https://fastapi.tiangolo.com/
[22]: https://www.kernel.org/doc/html/latest/filesystems/fuse.html
[23]: https://winfsp.dev/