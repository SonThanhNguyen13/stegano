# An Image Steganography Algorithm using Haar Discrete Wavelet Transform with Advanced Encryption System
## This code was insprired by [this](https://www.researchgate.net/publication/308881224_An_Image_Steganography_Algorithm_using_Haar_Discrete_Wavelet_Transform_with_Advanced_Encryption_System) work.
## Requirements:
    - Python3
## Install:
    pip3 install -r requirements.txt
## Usasage
 ### Gen key: 
    python3 gen_key.py
    output: key (key.txt), Initilization Vector (iv.txt)
 ### Encrypt: 
    python3 enc.py -i 'image_path' -k 'key_path' -v 'initilization_vector_path' (optional: -s 'save_dir', default: result/)
    output: A steganography image (.png), a difference matrix (.npy), message's length (len.txt)
 ### Decrypt: 
    python3 decr.py -i 'image_path' -k 'key_path' -v 'initilization_vector_path' -m 'difference_matrix_path' -l 'len_message_file_path'
 ### Original Image:
 <img src='https://user-images.githubusercontent.com/45412532/80194093-1798a800-8644-11ea-81f8-f99a0ce32c19.png'  width="250" height="500">
 
 ### Steganography Image: 
 <img src='https://user-images.githubusercontent.com/45412532/80194594-cdfc8d00-8644-11ea-9d8d-0587f660819d.png' width="250" height="500">

## Decrypt the original image:
 <img src = 'https://user-images.githubusercontent.com/45412532/80275663-02d41700-870d-11ea-9b13-e7365b95c99a.png' >

## Decrypt the stenography image:
 <img src = 'https://user-images.githubusercontent.com/45412532/80275684-1d0df500-870d-11ea-83be-8c612d753d1b.png'>


 
 

    
