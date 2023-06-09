# ParcialModificado
ParcialAct

Nombres: Wilson Javier Castro Contreras
Correo: w_castro@unisimon.edu.co
Nota: este es el parcial ya modificado, fue trabajado erroneamente en MundialPOO, es decir un proyecto desactualizado, por ello para probarlo correctamente se debe añadir esto al codigo:

    // Llamada al método UsersReg para verificar el usuario y la contraseña
        boolean sesionIniciada = seleccionDAO.UsersReg(usuario, clave);
    // Verificar si la sesión está iniciada
        if (!sesionIniciada) {
            JOptionPane.showMessageDialog(null, "No hay sesión iniciada");
            return;
        }
        
Cordiales saludos ;
