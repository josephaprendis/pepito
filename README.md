# pepito
Sub cambios()     For j = 1 To 21         nom_completo = Hoja1.Cells(j, 1)         anna = Hoja1.Cells(j, 2)         sexo = Hoja1.Cells(j, 3)                  letra = Mid(sexo, 1, 1)         numereo = Mid(anno, 3, 2)                           cantidad_caracteres = Len(nom_completo)                  nombre = ""                  For k = 1 To cantidad_caracteres             le = Mid(nom_completo, k, 1)             If le = "" Then              Exit For              Else              nombre = nombre &amp; le             End If         Next k                       Hoja1.Cells(j, 4) = nombre &amp; letra + numero                        Next j                        End Sub
