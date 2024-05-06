<template>
    <v-table theme="dark">
      <thead>
        <tr>
          <th class="text-left">
            Nome
          </th>
          <th class="text-left">
            Email
          </th>
        </tr>
      </thead>
      <tbody>
        <tr
          v-for="item in users"
          :key="item.nome"
        >
          <td>{{ item.nome }}</td>
          <td>{{ item.email }}</td>
        </tr>
      </tbody>
    </v-table>
  </template>



  <script>
  export default {
    data () {
      return {
        users: [
        { nome: "Ana Silva", email: "ana.silva@example.com" },
        { nome: "João Oliveira", email: "joao.oliveira@example.com" },
        { nome: "Maria Santos", email: "maria.santos@example.com" },
        { nome: "Pedro Costa", email: "pedro.costa@example.com" },
        { nome: "Sofia Pereira", email: "sofia.pereira@example.com" },
        { nome: "Tiago Rodrigues", email: "tiago.rodrigues@example.com" },
        { nome: "Carolina Martins", email: "carolina.martins@example.com" },
        { nome: "André Ferreira", email: "andre.ferreira@example.com" },
        { nome: "Inês Sousa", email: "ines.sousa@example.com" },
        { nome: "Luís Pereira", email: "luis.pereira@example.com" },
        { nome: "Mariana Almeida", email: "mariana.almeida@example.com" },
        { nome: "Diogo Fernandes", email: "diogo.fernandes@example.com" },
        { nome: "Beatriz Gomes", email: "beatriz.gomes@example.com" },
        { nome: "Francisco Carvalho", email: "francisco.carvalho@example.com" },
        { nome: "Catarina Ramos", email: "catarina.ramos@example.com" },
        { nome: "Miguel Oliveira", email: "miguel.oliveira@example.com" },
        { nome: "Rita Costa", email: "rita.costa@example.com" },
        { nome: "Guilherme Martins", email: "guilherme.martins@example.com" },
        { nome: "Patrícia Rodrigues", email: "patricia.rodrigues@example.com" },
        { nome: "Bruno Silva", email: "bruno.silva@example.com" },
        { nome: "Diana Gonçalves", email: "diana.goncalves@example.com" },
        { nome: "Rafaela Santos", email: "rafaela.santos@example.com" },
        { nome: "Daniel Sousa", email: "daniel.sousa@example.com" },
        { nome: "Carolina Ribeiro", email: "carolina.ribeiro@example.com" },
        { nome: "Hugo Fernandes", email: "hugo.fernandes@example.com" },
        { nome: "Ana Rita Silva", email: "ana.rita.silva@example.com" },
        { nome: "Ricardo Martins", email: "ricardo.martins@example.com" },
        { nome: "Sara Gonçalves", email: "sara.goncalves@example.com" },
        { nome: "Joana Sousa", email: "joana.sousa@example.com" },
        { nome: "Tiago Costa", email: "tiago.costa@example.com" },
        { nome: "Marta Santos", email: "marta.santos@example.com" },
        { nome: "André Rodrigues", email: "andre.rodrigues@example.com" },
        { nome: "Inês Pereira", email: "ines.pereira@example.com" },
        { nome: "Miguel Santos", email: "miguel.santos@example.com" },
        { nome: "Inês Costa", email: "ines.costa@example.com" },
        { nome: "Ricardo Silva", email: "ricardo.silva@example.com" },
        { nome: "Ana Sofia Santos", email: "ana.sofia.santos@example.com" },
        { nome: "Pedro Martins", email: "pedro.martins@example.com" },
        { nome: "Beatriz Rodrigues", email: "beatriz.rodrigues@example.com" },
        { nome: "João Pereira", email: "joao.pereira@example.com" },
        { nome: "Carolina Oliveira", email: "carolina.oliveira@example.com" },
        { nome: "Guilherme Silva", email: "guilherme.silva@example.com" },
        { nome: "Mariana Pereira", email: "mariana.pereira@example.com" },
        { nome: "Tomás Rodrigues", email: "tomas.rodrigues@example.com" },
        { nome: "Sofia Santos", email: "sofia.santos@example.com" },
        { nome: "Ana Carolina Silva", email: "ana.carolina.silva@example.com" },
        { nome: "Miguel Costa", email: "miguel.costa@example.com" },
        { nome: "Inês Martins", email: "ines.martins@example.com" },
        { nome: "Diogo Oliveira", email: "diogo.oliveira@example.com" },
        { nome: "Joana Martins", email: "joana.martins@example.com" }
        ],
      }
    },
  }
</script>