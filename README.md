blenc-1.1.3
===========

BLENC is an extension that permits you to protect PHP source scripts with Blowfish Encription. BLENC hooks into the Zend Engine, allowing for transparent execution of PHP scripts previously encoded with BLENC. It is not designed for complete security (it is still possible to disassemble the script into op codes using a package such as XDebug), however it does keep people out of your code(what I need it for) and make reverse engineering difficult.
