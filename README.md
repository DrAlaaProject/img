"# img ghanem has been updateed this project" 
test
Digital image processing

?	What is digital image processing?
Digital image processing:
                             is a method to convert an image into digital form and perform some operations on it, in order to get an enhanced image or to extract some information from it.
It is a type of signal dispensation in which input is image, like video frame or photograph and
output may be image or characteristics associated with that image.






















Medical image processing
        medical imaging is concerned with:
o	Interaction of all forms of radiation with tissue and non-invasive visualization of internal organs, tissue. 
o	The development of appropriate technology to extract clinically useful information, usually in the form of an image from the observed technology. 
Medical image processing deals with the development of problem-specific approaches to the enhancement of raw medical image data for the purposes of selective visualization as well as further analysis. 
(1).

?	Essential environments of a medical imaging system:

 
Figure 1
(2)
  


?	Goals of medical image analysis techniques:
?	Computer Aided Diagnosis (CAD): given measurements and features make a diagnosis. 
?	Help radiologists on their diagnosis procedure for accuracy and efficient.
?	Quantification: Measuring the features on medical images, 
e.g. helping radiologist obtain measurements from medical images.


Uses of digital image processing in medicine:
o	Projection X-ray (Radiography):
?	In NOV 8,1995 Wilhelm Konrad Rontgen was reported that discovery of a new ray.
?	In JAN 13,1896 the first clinical use of x rays by 2 British DRs to find a needle in a hand.
?	is two - dimensional images.              
 
Figure 2: this a sample of X-Ray slices.

o	X-ray Computed Tomography (CT):
?	In NOV 8,1895 G. Hounsfield (computer experts) and A.M Cormack(physicist).
1.	Provide 3D anatomical information
2.	Preserves topology (bones).
?	x-ray computed More focused and three - dimensional images. Any way both is One type of radiation.
?	But this is an excessive radiation and not good for all soft tissues.

 
Figure 3: 3D Reconstruction in CT
 
Figure 4: Sample CT Slices.


o	Magnetic Resonance Imaging (MRI):
?	Image Formation consist of Hydrogen nuclei (protons) under a strong magnetic field spin in phase with one another and align with the field.
?	 Relaxed protons induce a measurable radio signal.
?	Main modality for image guided surgery Superb ability to discriminate between subtle differences in tissue characteristics. 
?	Very safe.
?	 Less accurate for bone scanning.
 
Figure 5: Sample MRI.

o	Ultrasound:
?	Image Formation consists of an ultrasonic energy is propagated into the patient from a transducer placed on the skin and back-scattered echo signal is recorded by the same transducer.
?	 Clean, safe, expensive, Noisy, Gas filled and bony structures cannot be imaged because they absorb ultrasound waves.
 
Figure 6: Sample Ultrasound Image.

 
Figure 7: Sample Ultrasound Image.

o	Nuclear Medicine (PET):
?	Is Positron Emission Tomography Detection of radiation from the emission of positrons 1998-2001 Davide Townsend and Dr. Ron Knott:
1.	Detection of radiation from positron emission.
2.	valuable technology for certain diseases and disorders.
3.	 The amount of radiation is small - injection of radioactive materials (invasive).

 
Figure 8: Positron Emission Tomography (PET).

 
Figure 9: Sample PET Images.

o	Magnetic Resonance Angiography (MRA).
?	Magnetic Resonance Angiography Image Formation Imagine the blood vessels (moving spins) using MRI scanner.
1.	PCA (phase contract angiography) 
2.	CEA (contrast enhanced angiography) 
3.	CTA (computer tomography angiography)
4.	 DSA (digital subtraction angiograph TOF -(time-of-flight)
 
Figure 10






(3). 
?	Medical image processes:
o	Image enhancement:
?	Image enhancement is the process of adjusting images so that the results are more suitable for display or further image analysis. For example, you can remove noise, sharpen, or adjust the contrast of an image, making it easier to identify key features.
It is divided into: 
?	Spatial domain methods:
•	The term spatial domain refers to the aggregate of pixels composing an image. 
•	Spatial domain methods are procedures that operate directly on these pixels. 
•	Spatial domain processes will be denoted by the expression. 
G (x, y) = t [f (x, y)]
?	Enhancement filters in Spatial domain:
•	Point processing.
•	Median and max/min filtering.
•	IMAGE SUBTRACTION.
•	HISTOGRAM EQUALIZATION.

?	frequency domain methods:
•	We compute the Fourier transform of the image to be enhanced, multiply the result by a filter (rather than convolve in the spatial domain), and take the inverse transform to produce the enhanced image.
Enhancement filters in frequency domain:
?	IMAGE SMOOTHING.
?	Neighborhood Averaging.
?	Edge preserving smoothing.
?	Image sharpening.

















o	Image restoration:
?	Image restoration attempts to restore images that have been degraded (motion blur, focus blur, resolution).
?	Identify the degradation process and attempt to reverse it. 
?	Almost Similar to image enhancement, but more objective.

(4)

 
Figure 13
?	Image Restoration Filters:
?	The inverse filter. 
?	The Wiener filters. 
?	MAP formulation.

o	Image noise reduction and removing:
?	Noise sources:
1.	Image acquisition
2.	 Image transmission 
?	Noise models Spatially independent noise models
1.	Gaussian noise 
2.	Rayleigh noise 
3.	Erlang (Gamma) noise 
4.	Exponential noise 
5.	Impulse (salt-and-pepper) noise Spatially dependent noise model 
6.	Periodic noise

DIFFERENT TYPES OF FILTERS USED TO REMOVE THESE NOISES:
?	Adaptive Median Filter: AMF is a nonlinear filter. It uses varying window size for noise reduction. AMF fairs well at low and medium noise densities but blurs the image at high noise densities.
?	Median Filter: Median filter is a best order static, non- linear filter, whose response is based on the ranking of pixel values contained in the filter region.
?	Trimmed Median Filters: Trimmed median filter is used to reject the noise from the selected window. Alpha trimmed mean filter (ATMF) is a symmetric filter where the trimming is symmetric at both ends.
?	 Decision Based Algorithm: Processed pixel is identified as noisy if the pixel value is either 0 or 255; else it is considered as not noisy.

(5,6)                 














Reference: 
1.	Technology beyond the Dreams™ Copyright © 2006 Pantech Solutions Pvt For more details – www.pantechsolutions.net – http://www.slideshare.net/pantechsolutions – http://www.scribd.com/pantechsolutions – http://www.youtube.com/pantechsolutions
2.	https://www.csie.ntu.edu.tw/~b95041/biomedical/12_21_MIP2010.pdf.
3.	Technology beyond the Dreams™ Copyright © 2006 Pantech Solutions Pvt For more details
4.	Gonzalez & Woods-DIP Books • Prof. P.K. Biswas, IIT Kharagpur • Dr. ir.Aleksandra Pizurika, Universiteit Hent. • Gleb V. Teheslavski. • Yu Hen Yu. • Zhou Wang, University of Texas
5.	M. Tulin Y?ld?r?m, Alper Bas¸turk and M. Emin Yuksel, Impulse Noise Removal From Digital Imagesby a Detail-Preserving Filter Based on Type-2 Fuzzy Logic, IEEE transactions on fuzzy systems, pp-920-928, 2008. 
6.	H. Ibrahim, “Adaptive switching median filter utilizing quantized window size to remove impulse noise from digital images,” Asian Transactions on Fundamentals of Electronics, Communication & Multimedia, vol. 2, no. 1, pp. 1-6, March 2012.




