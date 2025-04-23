### Liên hệ giữa $\vec{E}$ và điện thế V
$$\vec{E} = -\nabla V$$
#### Grad trong các hệ toạ độ 
##### Hệ Decartes $(x, y, z)$
$$\nabla = \left( \frac{\partial}{\partial x}, \frac{\partial}{\partial y}, \frac{\partial}{\partial z} \right)$$
##### Hệ trụ $(\rho, \phi, z)$
$$\nabla = \left( \frac{\partial}{\partial \rho}, \frac{1}{\rho}\frac{\partial}{\partial \phi}, \frac{\partial}{\partial z} \right)$$
##### Hệ cầu $(r, \theta, \phi)$
$$\nabla = \left( \frac{\partial}{\partial r}, \frac{1}{r}\frac{\partial}{\partial \theta}, \frac{1}{r\sin\theta}\frac{\partial}{\partial \phi} \right)$$
### Liên hệ giữa $\vec{E}$ và mật độ điện tích $\rho$
Theo định luật Gauss :
$$\nabla \cdot \vec{E} = \frac{\rho}{\varepsilon}$$
Trong đó : 
- $\rho$ là mật độ điện tích.
- $\varepsilon = \varepsilon_{0}\cdot \varepsilon_{r}$ 
#### Toán tử divergence $\nabla \cdot$ trong các hệ toạ độ :
##### Hệ Descartes :
$$\nabla \cdot \vec{A} = \frac{\partial A_x}{\partial x} + \frac{\partial A_y}{\partial y} + \frac{\partial A_z}{\partial z}$$
##### Hệ trụ : 
$$\nabla \cdot \vec{A} = \frac{1}{\rho}\frac{\partial (\rho A_\rho)}{\partial \rho} + \frac{1}{\rho}\frac{\partial A_\phi}{\partial \phi} + \frac{\partial A_z}{\partial z}$$
##### Hệ cầu : 
$$\nabla \cdot \vec{A} = \frac{1}{r^2}\frac{\partial (r^2 A_r)}{\partial r} + \frac{1}{r\sin\theta}\frac{\partial (\sin\theta A_\theta)}{\partial \theta} + \frac{1}{r\sin\theta}\frac{\partial A_\phi}{\partial \phi}$$
### Liên hệ giữa $\mathbf{E}$ và  $\mathbf{B}$
$$\nabla \times \mathbf{E} = - \frac{\partial \mathbf{B}}{\partial t}$$
### Liên hệ giữa $V$ và $\rho$
Phương trình Poisson:
$$\nabla^2V = -\frac{\rho}{\varepsilon}$$
Trong đó : 
- $\rho$ là mật độ điện tích.
- $\varepsilon = \varepsilon_{0}\cdot \varepsilon_{r}$
#### Toán tử Laplace $\nabla^2$ trong các hệ toạ độ :
##### Hệ Decartes :
$$\nabla^2 V = \frac{\partial^2 V}{\partial x^2} + \frac{\partial^2 V}{\partial y^2} + \frac{\partial^2 V}{\partial z^2}$$ 
##### Hệ trụ :
$$\nabla^2 V = \frac{1}{\rho}\frac{\partial}{\partial \rho}\left( \rho \frac{\partial V}{\partial \rho} \right) + \frac{1}{\rho^2}\frac{\partial^2 V}{\partial \phi^2} + \frac{\partial^2 V}{\partial z^2}$$
##### Hệ cầu :
$$\nabla^2 V = \frac{1}{r^2}\frac{\partial}{\partial r}\left( r^2 \frac{\partial V}{\partial r} \right) + \frac{1}{r^2\sin\theta}\frac{\partial}{\partial \theta}\left( \sin\theta \frac{\partial V}{\partial \theta} \right) + \frac{1}{r^2\sin^2\theta}\frac{\partial^2 V}{\partial \phi^2}$$
### Liên hệ giữa $\vec{B}$ và $\vec{J}$
Theo định luật Ampere : 
$$\nabla \times \mathbf{H} = \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t}$$
Trong đó : 
- $\mathbf{J}$ là vector mật độ dòng điện.
Xét trong từ trường tĩnh *(không xét dòng điện dịch chuyển tức thời)*
$$\nabla \times \mathbf{B} = \mu_{0} \mathbf{J}$$
Trong đó : 
- $\mathbf{B} = \mu_{0}\mu_{r}\mathbf{H}$ : Là cảm ứng từ.
- $\mu_{0} = 4\cdot 10^{-7} \ (H/m)$ : Độ thẩm từ của chân không.
#### Toán tử curl (rot) $\nabla \times$ trong các hệ toạ độ : 

##### Hệ Descartes :
$$\nabla \times \vec{A} = \left( \frac{\partial A_z}{\partial y} - \frac{\partial A_y}{\partial z}\right)\mathbf{e_{x}} + \left( \frac{\partial A_x}{\partial z} - \frac{\partial A_z}{\partial x}\right)\mathbf{e_{y}} + \left( \frac{\partial A_y}{\partial x} - \frac{\partial A_x}{\partial y} \right)\mathbf{e_{z}}$$
##### Hệ trụ : 
$$\nabla \times \vec{A} = \left( \frac{1}{\rho}\frac{\partial A_z}{\partial \phi} - \frac{\partial A_\phi}{\partial z}\right)\mathbf{e_{\rho}}+\left(\frac{\partial A_\rho}{\partial z} - \frac{\partial A_z}{\partial \rho}\right)\mathbf{e_{\varphi}} + \left( \frac{1}{\rho}\left( \frac{\partial (\rho A_\phi)}{\partial \rho} - \frac{\partial A_\rho}{\partial \phi} \right) \right)\mathbf{e_{z}}$$
##### Hệ cầu : 
$$\nabla \times \vec{A} = \frac{1}{r\sin\theta} \left( \frac{\partial (A_\phi \sin\theta)}{\partial \theta} - \frac{\partial A_\theta}{\partial \phi} \right) \mathbf{e}_{r} + \frac{1}{r} \left( \frac{1}{\sin\theta}\frac{\partial A_r}{\partial \phi} - \frac{\partial (r A_\phi)}{\partial r} \right) \mathbf{e}_{\theta} + \frac{1}{r} \left( \frac{\partial (r A_\theta)}{\partial r} - \frac{\partial A_r}{\partial \theta} \right) \mathbf{e}_{\phi}$$
### Từ thông 
$$\Phi_{\mathbf{B}} = \int_{S}\mathbf{B}\cdot d\mathbf{S}$$
#### Cảm ứng điện từ 
$$\mathcal{E} = \frac{d\Phi}{dt}$$
### Vector từ thế $\vec{A}$
$$\mathbf{B} = \nabla \times \mathbf{A}$$
