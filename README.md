# autocompressor
Autoencoder Tool for Compressing and Decompressing Files

## Installation

install using `pip install autocompressor`

## Usage

```
$ autocompressor [action] [file(s)] [options]
```
actions: 

  -c, --compress: compress files into encoded data and decompression model
  
      File Requirements:
      
        -o, --original: file to be compressed
        
  -d, --decompress: restore original
  
      File Requirements:
      
        -e, --encoded: encoded data
        
        -m, --model: decoder model
        
  -v --verify: check parity between original and decompressed
  
      File Requirements:
      
        -o, --original: original file
        
        -r, --restored: decompressed file
        
  -cd, --compress-directory: compresses all files in target directory
  
      File Requirements:
      
         -p, --path: path to target directory
         
  -dd, --decompress-directory: decompresses all the encoded files in a target directory
  
      File Requirements:
      
        -p, --path: path to compressed directory file
        
  
 options:
 
    -od, --output_directory: directory to create files in
    
