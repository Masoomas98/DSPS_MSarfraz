For this homework i worked with Paula, discussed data wrangling with Miles and Sarah and Sid helped me figure out that i need to change my initial guesses instead of changing kernels everytime.

The homework was about Gaussian Regression Process, GPR is a versatile technique that finds applications in a wide range of fields where regression, uncertainty estimation, and data modeling are important components of the problem-solving process. It is particularly valuable when dealing with small datasets or when uncertainty in predictions is critical. Choosing kernel is kind of tricky that can go well with the given data set. In my case i chose Matern32Kernel, as it was the only one working better than the others. I still think there might be a better one to work with. The interpolating task went well however the extrapolation wasn't predicted quite well, i assume that could be because of my choice of kernel and initial guess. The data was basicaaly the sea surface temperatures for 12 months for the years 1950 to 2010 and we had to interpolate in between the months for any day and extrapolate beyong 2010 to 2030 to see the trend of temperatures.

The most tricky/ difficult part for me was to choose which kernel to make it work it kept giving me very dissapointing values , initially it seemed my predictions were not anywhere near the real data, that's where Sid suggested me to play with kernels and initial guesses. Paula and I worked together to figure out what kernel we should go with.

The easier part was ofcourse visualising the data basically part 1 of assignment. 

I learned a few things about how to apply gaussian processed to the data which i am still not fully confident about i might need more practice and in depth understanding of it's importance.
