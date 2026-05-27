# Codigos - Ingeniería física
## Repositorio basado en los diferentes desarrollos a lo largo de diferentes cursos. Especialemente en instrumentos ópticos.

Trabajamos en la simulacion de diferentes fenomenos ópticos que se dan en el proceso de formación de imagenes, y la forma en que diferentes elementos intervienen en el espacio de Fourier, las operaciones que se usan en estos espacios y su efecto en la imagen formada.

Usaremos librerias tales como:

numpy
scipy
from scipy.fft import fft2
from scipy.fft import ifft2
from scipy.fft import fftfreq
from scipy.fft import fftshift, ifftshift
import imageio
import PIL
from PIL import Image, ImageFilter, ImageDraw, ImageFont
import cv2

import matplotlib.pyplot as plt
from matplotlib.colors import LinearSegmentedColormap
from matplotlib import animation
from matplotlib.animation import PillowWriter
import pint

from PIL import Image

Tanto para la aplicacion de operaciones complejas como para la manipulacion de matrices de pixeles y grafiación.
