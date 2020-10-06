# Membrane-substrate distance

#### Studing the adhesion state of giant unilamellar vesicles using reflection interference contrast microscopy (RICM):
The effective reflection coefficient:
$$R = r_{01} + [(1-r_{01}^2) e^{-i k \Delta_1}]r_{12} + [(1-r_{01}^2)(1-r_{12}^2) e^{-i k (\Delta_1 + \Delta_2)}]r_{23} + [(1-r_{01}^2)(1-r_{12}^2)(1-r_{23}^2) e^{-i k (\Delta_1 + \Delta_2 + \Delta_3)}]r_{34}$$
#### where:
$$ r_{ij} = \frac{n_i - n_j}{n_i + n_j} \ ,\  k = \frac{2 \pi}{\lambda} \ ,\ \Delta_i = 2 n_i d_i$$

$n_i$: refractive index of the layer i 

$\lambda$: wavelength of incident light = 546 nm

$d_i$: thicknesses of the layers transversed by the light

#### The objective is to determine the height of the vesicle membrane on the substrate:
$$h = d_2$$

#### To get the relation between intensity and height we fit with the cosine function
$$R_{norm} = y_0 - A \cos \left(\frac{4 \pi n_2}{\lambda} (h - h_0) \right)$$