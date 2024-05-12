# Simulate Colorblindness and Correct Colors for People with Colorblindness

This Script simulates images based on how people with colorblindness would perceive it naturally. You can also vary the degree of colorblindness for simulating. This script can also be used to correct images, making differenciation of certain colors in an image easier for people with colorblindness.

* **Easy** to setup and run!
* Simulate **Protanopia, Deutranopia, Tritanopia and Hybrid Colorblindess (Protanopia+Deutranopia).**
* **Correct colors** in images for **Protanopia, Deutranopia and Hybrid Colorblindness.**
* **Vary the degree of colorblindness** for both Simulation and Correction!
* Extremly **fast.**
* Use it from the **command line (super easy)**, or use it as a **library (advanced users).**
* Supports **Daltonization and HSV Shifting algorithm.**




## Example Simulation Results: 

### Original Image:
![example_original](https://user-images.githubusercontent.com/9898343/113453323-c0fb2880-93d3-11eb-8c5f-1df504233313.jpg)

### Simulating Protanopia, Degree = 1.0:
![example_simulate_protanopia](https://user-images.githubusercontent.com/9898343/113453334-c6587300-93d3-11eb-8bc7-b14317aa84e2.png)

### Simulating Deutranopia, Degree = 1.0:
![example_simulate_deutranopia](https://user-images.githubusercontent.com/9898343/113453346-c9536380-93d3-11eb-99c3-08a6a3cfb7d6.png)

### Simulating Tritanopia, Degree = 1.0:
![example_simulate_tritanopia](https://user-images.githubusercontent.com/9898343/113453354-cd7f8100-93d3-11eb-8349-ad58e030cbf2.png)

### Simulating Hybrid ColorBlindness, Protanopia_degree = Deutranopia_degree = 0.5
![example_simulate_hybrid](https://user-images.githubusercontent.com/9898343/113453912-02d89e80-93d5-11eb-8a5b-575b92f99eb6.png)


## Example Correction Results:
Here, we will first correct the images, and then simulate the corrected image, to see if the difference is noticable.

### Protanopia

#### Correcting for Protanopia, Protanopia_degree = 0.9, Deutranopia_degree = 0.0
![ex_corrected_protanopia](https://user-images.githubusercontent.com/9898343/113454436-3831bc00-93d6-11eb-9f11-34167fdec3b5.png)

#### Simulating the corrected image for protanopia. Protanopia_degree = 0.9.
![ex_simulate_corrected_protanopia](https://user-images.githubusercontent.com/9898343/113454441-3bc54300-93d6-11eb-9761-5468fa2e70e2.png)

### Deutranopia

#### Correcting for Deutranopia, Deutranopia_degree = 0.9, Protanopia_degree = 0.0
![ex_corrected_deutranopia](https://user-images.githubusercontent.com/9898343/113454444-41228d80-93d6-11eb-999e-aff3e2434fc5.png)

#### Simulating the corrected image for Deutranopia. Deutranopia_degree = 0.9.
![ex_simulate_corrected_deutranopia](https://user-images.githubusercontent.com/9898343/113454461-45e74180-93d6-11eb-88b7-caed402e949c.png)


