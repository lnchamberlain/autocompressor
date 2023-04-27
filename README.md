# autocompressor
Autoencoder Tool for Compressing and Decompressing Files

## Installation

install using `pip install autocompressor`

## Usage

```
$ autocompressor [action] [file(s)] [options]
```
actions: 

  -c, --compress: File to be compressed -c [FILE]
        
  -d, --decompress: Encoded pickle file to be decompressed -d [ENCODED-FILE.pckl], decompression model must be in same directory and be named {encoded-file-name}-model.pckl
  
        
  -v --verify: Verify the decompression of a file -v [ORIGINAL-FILE] [DECOMPRESSED-FILE]
  
  -cd, --compress-directory: Compress all files in directory -cd [PATH]
         
  -dd, --decompress-directory: Decompress all compressed files in a directory -dd [PATH]
 
 options:
 
    -od, --output_directory: Path to output directory if not cwd -od [PATH]
    
