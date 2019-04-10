<template>
	<v-layout align-center justify-space-around row fill-height wrap >
		<v-flex xs12 sm6 md4 lg3 v-for="variavel in vetor">
		    <v-card :color="variavel.color">
		    	<v-btn color="primary" to="/login">Teste</v-btn>
		        {{variavel.text}}
		    </v-card>
		</v-flex>
    </v-layout>
</template>
<script type="text/javascript">
export default{
	data(){
		return{
		    vetor: [
		      { 
		      	text: 'Bom dia',
		        color: 'yellow'
		  	  },
		      { text: 'Boa Tarde' 
		  ,
		        color: 'pink'},
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		      { text: 'Bom dia' },
		      { text: 'Boa Tarde' },
		      { text: 'Boa noite' },
		    ]
		}
	}
}

</script>
<style type="text/css">
	.teste{
		background-color: red !important;
	}
</style>