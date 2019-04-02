<template>
  <v-data-table
    :headers="headers"
    :items="trips"
    class="elevation-1"
  >
    <template v-slot:items="props">
      <td>{{ props.item.driverId }}</td>
      <td>{{ props.item.driverName }}</td>
      <td>{{ props.item.carId }}</td>
      <td>{{ props.item.water }}</td>
      <td>{{ props.item.oil }}</td>
      <td>{{ props.item.tilePressure }}</td>
    </template>
  </v-data-table>
</template>

<script>
  export default {
    data () {
      return {
        headers: [
          { text: 'Driver ID', value: 'driverId' },
          { text: 'Driver Name', value: 'driverName' },
          { text: 'Car ID', value: 'carId' },
          { text: 'Water', value: 'water' },
          { text: 'Oil', value: 'oil' },
          { text: 'Tile pressure', value: 'tilePressure' }
        ],
        trips: [
          {
            driverId: '8102394',
            driverName: 'David Gershon',
            carId: '3294752',
            water: true,
            oil: false,
            tilePressure: '36.2'
          },
          {
            driverId: '8475974',
            driverName: 'David Ramon',
            carId: '4356439',
            water: true,
            oil: false,
            tilePressure: '15.2'
          },
          {
            driverId: '5004354',
            driverName: 'Ophir Elias',
            carId: '23434534',
            water: true,
            oil: false,
            tilePressure: '12.2'
          },
          {
            driverId: '7003943',
            driverName: 'Yuval Shpigel',
            carId: '9774359',
            water: true,
            oil: false,
            tilePressure: '30.2'
          },
          {
            driverId: '7546382',
            driverName: 'Dani Neemani',
            carId: '8582784',
            water: false,
            oil: false,
            tilePressure: '4.2'
          },
          {
            driverId: '8000021',
            driverName: 'David Gershon',
            carId: '8574893',
            water: true,
            oil: true,
            tilePressure: '11.2'
          },
        ]
      }
    }
  }
</script>