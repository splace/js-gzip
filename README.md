STOP just tested some long files and inflate routine above seems to have some bugs!! 

parses gzip wrapper and uses the inflate routine from here; http://www.codeproject.com/KB/scripting/Javascript_binaryenc.aspx to return the uncompressed data. (this includes unicode support) fundamentally uses streams to keep memory usage low and intended to be used efficiently through callback events. ideal for decompressing files loaded into html dynamically, ajax.

