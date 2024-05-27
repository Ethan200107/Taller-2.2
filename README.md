# Taller-2.2
ethan alexis Astorga Contreras , 20718176-5 , ethan.astorga@alumnos.ucn.cl
ignacio Hector Cruz Reyes , 21127029-2 ,  ignacio.cruz01@alumnos.ucn.cl

se crean los objetos de los productos:
{Categoria,[Subcategoria{Productos}]}
estan ordenados de la siguiente manera
categoria , subcategoria, nombre producto, valor producto;
{Medicamentos,Analgésicos,Ibuprofeno 400 mg,500}
{Medicamentos,Analgésicos,Paracetamol 500 mg,300}
{Medicamentos,Antihistamínicos,Loratadina 10 mg,700}
{Medicamentos,Antihistamínicos,Cetirizina 5 mg,600}
{Cuidado Personal,Higiene Bucal,Pasta Dental Colgate Total 12,300}
{Cuidado Personal,Higiene Bucal,Cepillo de Dientes Oral-B Pro,200}
{Cuidado Personal,Cuidado de la Piel,Crema Hidratante Neutrogena,1000}
{Cuidado Personal,Cuidado de la Piel,Protector Solar Nivea SPF 50,1200}
{Vitaminas y Suplementos,Vitaminas,Vitamina C 1000 mg,400}
{Vitaminas y Suplementos,Vitaminas,Vitamina D3 1000 UI,500}
{Vitaminas y Suplementos,Suplementos Nutricionales,Proteína en Polvo sabor chocolate,800}
{Vitaminas y Suplementos,Suplementos Nutricionales,Omega 3 cápsulas,900}
{Primeros Auxilios,Material de Curación,Venda Elástica,200}
{Primeros Auxilios,Material de Curación,Gasas Estériles,150}
{Primeros Auxilios,Desinfectantes,Alcohol 70%,100}
{Primeros Auxilios,Desinfectantes,Solución de Yodo,120}
{Cuidado del Bebé,Pañales y Toallitas,Pañales Pampers Talla 1,150}
{Cuidado del Bebé,Pañales y Toallitas,Toallitas Húmedas Huggies,80}
{Cuidado del Bebé,Alimentación,Leche en Polvo para Bebés,300}
{Cuidado del Bebé,Alimentación,Puré de Manzana Gerber,250}

txt para la lectura en el codigo: 
Medicamentos,Analgésicos,Ibuprofeno 400 mg,500
Medicamentos,Analgésicos,Paracetamol 500 mg,300
Medicamentos,Antihistamínicos,Loratadina 10 mg,700
Medicamentos,Antihistamínicos,Cetirizina 5 mg,600
Cuidado Personal,Higiene Bucal,Pasta Dental Colgate Total 12,300
Cuidado Personal,Higiene Bucal,Cepillo de Dientes Oral-B Pro,200
Cuidado Personal,Cuidado de la Piel,Crema Hidratante Neutrogena,1000
Cuidado Personal,Cuidado de la Piel,Protector Solar Nivea SPF 50,1200
Vitaminas y Suplementos,Vitaminas,Vitamina C 1000 mg,400
Vitaminas y Suplementos,Vitaminas,Vitamina D3 1000 UI,500
Vitaminas y Suplementos,Suplementos Nutricionales,Proteína en Polvo sabor chocolate,800
Vitaminas y Suplementos,Suplementos Nutricionales,Omega 3 cápsulas,900
Primeros Auxilios,Material de Curación,Venda Elástica,200
Primeros Auxilios,Material de Curación,Gasas Estériles,150
Primeros Auxilios,Desinfectantes,Alcohol 70%,100
Primeros Auxilios,Desinfectantes,Solución de Yodo,120
Cuidado del Bebé,Pañales y Toallitas,Pañales Pampers Talla 1,150
Cuidado del Bebé,Pañales y Toallitas,Toallitas Húmedas Huggies,80
Cuidado del Bebé,Alimentación,Leche en Polvo para Bebés,300
Cuidado del Bebé,Alimentación,Puré de Manzana Gerber,250

todos estos objetos se guardan en hasmap_Productos.

se crean los objetos cliente:
Cliente pide: rut , tiene discapacidad , cual es su discapacidad
{12345678-9,No,No tiene discapacidad}
{23456789-0,Si,Tercera Edad}
{34567890-1,Si,Embarazada}
{45678901-2,Si,Discapacitado}
{56789012-3,No,No tiene discapacidad}
{67890123-4,Si,Embarazada}
{78901234-5,No,No tiene discapacidad}
{89012345-6,Si,Discapacitado}
{90123456-7,No,No tiene discapacidad}
{01234567-8,Si,Discapacitado}
{12345678-9,No,No tiene discapacidad}
{23456789-0,Si,Tercera Edad}
{34567890-1,No,No tiene discapacidad}
{45678901-2,Si,Discapacitado}
{56789012-4,No,No tiene discapacidad}
{23456789-1,Si,Tercera Edad}
{34567890-0,No,No tiene discapacidad}
{45678901-8,Si,Discapacitado}
{56789012-6,No,No tiene discapacidad}

todos estos objetos se guardan en un queue<Cliente*>.

txt para la lectura en el codigo:
12345678-9,No,No tiene discapacidad
23456789-0,Si,Tercera Edad
34567890-1,Si,Embarazada
45678901-2,Si,Discapacitado
56789012-3,No,No tiene discapacidad
67890123-4,Si,Embarazada
78901234-5,No,No tiene discapacidad
89012345-6,Si,Discapacitado
90123456-7,No,No tiene discapacidad
01234567-8,Si,Discapacitado
12345678-9,No,No tiene discapacidad
23456789-0,Si,Tercera Edad
34567890-1,No,No tiene discapacidad
45678901-2,Si,Discapacitado
56789012-4,No,No tiene discapacidad
23456789-1,Si,Tercera Edad
34567890-0,No,No tiene discapacidad
45678901-8,Si,Discapacitado
56789012-6,No,No tiene discapacidad

el codigo se ejecuta primero leyendo ambos txt, luego ingresar a un menu donde se tiene distintas opciones
1. ingresar cliente :  donde se ingresa un nuevo cliente
2.Llamar al siguiente cliente: donde se llama al siguiente cliente
3. carrito del cliente: donde se podra ingresar, eliminar o ver el carrito del cliente
4. se cancela la venta del cliente actual
5. se genera una boleta para la venta
6. se ingresa al menu de la bodega
7. se guarda y sale del programa

menu de bodega
1. se agrega un nuevo producto al stock
2. se elimina un producto del stock
3. se puede ver el inventario
4. se sale del menu de bodega
