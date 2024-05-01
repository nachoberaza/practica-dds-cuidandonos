# Cálculo de demora

```pseudo
class Ruta{
    private paradas : list<Paradas>
    private estrategiaDeSeguimiento

    public calcularDuracion(){
        estrategiaDeSeguimiento.calcularDemora(Paradas)
    }
}

class EstrategiaDeSeguimientoPorParadas{

    public calcularDemora(paradas list<Paradas>) Integer{
        for each parada in paradas{
            demoraTotal += calcularDemoraPorTramo(parada, paradaSiguiente)
        }
        return demoraTotal
    }

    public calcularDemoraPorTramo(parada1: Parada, parada2: Parada){
        //calculo de demora
    }

}
```