use linux tool xxd (man xxd for usage) to create a hexdump for this image file. The flag is in the hexdump. 

Note:This is a simple but actually interesting problem because my first attempt was to look for hexdecimal ffd9 which stands
for the end of the JPEG file (ending bytes). I thought there could be extra information after this ending bytes but it turns
out that the flag is right over there with the image intact.
