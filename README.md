# ImageMagickToPNG
Simple command for recursively convert images to .PNG  in Windows CMD (especially usefull for the whatsapp image not opening in Adobe Apps issue).
FOR /R %a in (*.jpeg) do magick.exe mogrify -format png "%~a"
