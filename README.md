# Taller Académico: Despliegue de VM con Terraform

**Autor**:  
LUIS MANUEL ROJAS CORREA  
Código: A00399289

---

## Objetivo del repositorio

Este repositorio contiene un script de **Terraform** (`main.tf`) que permite desplegar una **máquina virtual (VM) básica** en la nube (por ejemplo, Azure, AWS o GCP — dependiendo de la configuración del archivo).

Se utilizó como parte de un taller académico para aprender los fundamentos de:

- Infraestructura como Código (IaC)
- Automatización de recursos en la nube
- Uso básico de Terraform: `init`, `plan`, `apply`, `destroy`

---

## 🛠 ¿Qué hace el archivo `main.tf`?

Define y crea automáticamente:

- Una red virtual y subred.
- Una máquina virtual con sistema operativo (ej: Ubuntu).
- Reglas de firewall para permitir acceso (SSH, HTTP, etc.).
- IP pública para acceder a la VM.

---

## Uso académico

Este proyecto **no está pensado para producción**, sino como ejercicio de aprendizaje en entornos controlados y educativos.

---

 **Entregado por**: LUIS MANUEL ROJAS CORREA (A00399289)  
 *Taller de infraestructura en la nube*
