# Conversor de temperatura
Portugol Studio

    programa {
      funcao inicio() {

        real celcius, fahrenheit, kelvin

        escreva("Digite a temperatura em celcius: ")
        leia(celcius)

        fahrenheit = (celcius * 1.8) + 32 
        kelvin = (celcius + 273)
        escreva("Fahrenheit: ", fahrenheit, "\n")
        escreva("Kelvin: ", kelvin, "\n")
      }
    }
