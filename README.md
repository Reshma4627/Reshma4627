- 👋 Hi, I’m @Reshma4627
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Reshma4627/Reshma4627 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link tfrom PIL import Image

def encrypt_image(input_path, output_path, key):
    img = Image.open(input_path)
    
    pixels = img.load()

    width, height = img.size

    for i in range(width):
        for j in range(height):
            r, g, b = pixels[i, j]

            # swapping red and blue channels
            encrypted_pixel = (b, g, r)

            pixels[i, j] = encrypted_pixel

    img.save(output_path)
    print("Image encrypted successfully!")

def decrypt_image(input_path, output_path, key):
    img = Image.open(input_path)
    pixels = img.load()

    width, height = img.size

    for i in range(width):
        for j in range(height):
            r, g, b = pixels[i, j]

            # swapping red and blue channels back
            decrypted_pixel = (b, g, r)

            pixels[i, j] = decrypted_pixel

    img.save(output_path)
    print("Image decrypted successfully!")

 # image path
input_image = r"C:\Users\kolar\OneDrive\Pictures\Camera Roll\IMG.webp"
encrypted_image = r"C:\Users\kolar\OneDrive\Pictures\Camera Roll\encrypted img.bmp"
decrypted_image = r"C:\Users\kolar\OneDrive\Pictures\Camera Roll\decrypted img.bmp"


# Encrypt the image
encrypt_image(input_image, encrypted_image, key=None)

# Decrypt the image
decrypt_image(encrypted_image, decrypted_image, key=None)
o take a look at your changes.
--->
