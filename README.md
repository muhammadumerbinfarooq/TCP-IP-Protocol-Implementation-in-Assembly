<h1>TCP/IP Protocol Implementation in Assembly</h1>

<p>This repository contains a basic implementation of the TCP/IP protocol in Assembly language for x86 architecture.</p>

<h2>Features</h2>

<ul>
    <li>TCP/IP protocol implementation in Assembly language</li>
    <li>Supports socket initialization, binding, listening, accepting, sending, and closing</li>
    <li>Error handling for socket operations</li>
</ul>

<h2>Requirements</h2>

<ul>
    <li>x86 architecture</li>
    <li>Linux operating system</li>
    <li>NASM assembler</li>
</ul>

<h2>Usage</h2>

<ol>
    <li>Assemble the code using NASM: <code>nasm -f elf32 tcp_ip.asm -o tcp_ip.o</code></li>
    <li>Link the object file: <code>ld -m elf_i386 -s -o tcp_ip tcp_ip.o</code></li>
    <li>Run the program: <code>./tcp_ip</code></li>
</ol>

<h2>Author</h2>

<p><a href="(link unavailable)">MUHAMMAD UMER BIN FAROOQ</a></p>
