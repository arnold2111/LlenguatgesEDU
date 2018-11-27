Llenguatges EDU

Practica-Edu-1

Exercici 1.-Realitza una recerca per Internet , per tal d'esbrinar quins són els llenguatges de programació que en aquest moment s'estan utilitzant més en el mercat.

Java:

Java és un llenguatge de programació de propòsit general, concurrent, orientat a objectes, que va ser dissenyat específicament per tenir tan poques dependències d'implementació com fos possible. La seva intenció és permetre que els desenvolupadors d'aplicacions escriguin el programa una vegada i ho s'executin en qualsevol dispositiu

C ++:

C ++ és un llenguatge de programació dissenyat el 1979 per Bjarne Stroustrup. La intenció de la seva creació va ser el estendre al llenguatge de programació C mecanismes que permeten la manipulació d'objectes. En aquest sentit, des del punt de vista dels llenguatges orientats a objectes, el C ++ és un llenguatge híbrid.

CSharp:

CSharp és un llenguatge de programació orientat a objectes desenvolupat i estandarditzat per Microsoft com a part de la seva plataforma .NET, que després va ser aprovat com un estàndard per la ECMA

Exercici 2.-Amplia els coneixements sobre tres llenguatges que triïs dels mencionats anteriorment i introdueix un exemple de codi.

1.- >Java

	Exemple : printf(“Hola mundoo”);
	Exemple :
	private int caselles = 20;
	   for(int i; i<caselles;i++){
		 system.out.println("Aquesta es la casella"+ i);
	}

	Exemple :
	int[] numeros={2, -4, 15, -25};
	String[] nombres={"Juan", "José", "Miguel", "Antonio"};
	for(int i=0; i<nombres.length; i++){
	  System.out.println(nombres[i]);
	}

2.- >C

Exemple: 
	
	system.out.println(“Hola mundoo”);
	
Exemple :
	
	#include <stdio.h>
	int main(void)
	{
		char resultado; /* Variable de tipo carácter donde se almacenará el resultado de las operaciones.

	resultado=5+2; /*Realizamos una suma.*/
	printf("Resultado de la suma: %i\n",resultado);
	resultado=5-2; /*Realizamos una resta.*/
	printf("Resultado de la resta:%i\n",resultado);
	resultado=5*2; /*Realizamos una multiplicación.*/
	printf("Resultado de la multiplicación: %i\n",resultado);
	resultado=5/2; /*Realizamos una división entera.*/
	printf("Resultado de la división:%i\n",resultado);

	return(0); /* Salimos del programa con el código 0 porque no ha habido errores.

}


3.- >CSharp

Exemple : 

	Console.WriteLine(“Hola Mundo”);

Exemple :

	using System;
	using System.Collections.Generic;
	using System.Linq;
	using System.Text;
	using System.Threading.Tasks;

	namespace ejercicio3
	{
	    class Camisas
	    {
		int camisas;
		float precio;
		public void Ingresar()
		{
		    Console.WriteLine("INGRESE NUMERO DE CAMISAS");
		    camisas = int.Parse(Console.ReadLine());
		    Console.WriteLine("INGRESE PRECIO DE LAS CAMISAS");
		    precio = float.Parse(Console.ReadLine());
		}
		public void Trabajo()
		{
		    if (camisas >= 3)
		    {
			float a = (precio * 20) / 100;
			float b = precio - a;
			Console.WriteLine("DESCUENTO 20% PRECIO ES:  "+ b);

		    }
		    else
		    {
			float a = (precio * 01) / 100;
			float b = precio - a;
			Console.WriteLine("DESCUENTO 20% PRECIO ES:  " + b);
		    }
		    Console.ReadKey();
		}
		static void Main(string[] args)
		{
		    Camisas sem = new Camisas();
		    sem.Ingresar();
		    sem.Trabajo();

		}
	    }
	}

Exercici 3.-Busca llenguatges de programació del següent tipus.

Llenguatjes orientats a obejctes:

## Ada
## C++
## C#
## VB.NET
## Clarion
## Delphi
## Eiffel
## Java
## Objective-C
## Ocaml
## Oz
## PHP
## PowerBuilder
## Python
Exemple : 

	-*- coding: utf-8 -*-

	def multiple(valor, multiple):

	    """

	    Funcion para calcular si el numero es multiplo

	    utilizando el modulo de la division

	    """

	    resto = valor % multiple

	    if resto == 0:

		return True

	    else:

		return False



	# lista que contendra los valores multiples

	multiples_3=[]

	multiples_5=[]



	# bucle del 1 al 100

	for i in range(1,101):



	    if multiple(i,3):

		multiples_3.append(i)



	    if multiple(i,5):

		multiples_5.append(i)



	print "Los multiples de 3 son:", multiples_3

	print ""

	print "Los multiples de 5 son:", multiples_5

Ruby
Smalltalk

# Llenguatjes orientats a servidors:

## Perl

## ASP
	Exemple :

	<html>

	  <body>
	    <%
	      Dim h
	      h = hour(now())

	      response.write("<p>" & now())
	      response.write(" (Hora de Madrid (España)) </p>")

	      If h <  12 then
		      response.write("¡Buenos Dias!")
		else
		      response.write("¡Buenas tardes!")
	      end if
	    %>
	  </body>

	</html>
## JSP

## PHP
	Exemple :
	<?php
	// Esto:
	$a = array( 'color' => 'red',
		    'taste' => 'sweet',
		    'shape' => 'round',
		    'name'  => 'apple',
		    4        // la clave será 0
		  );

	$b = array('a', 'b', 'c');

	// . . .es completamente equivalente a
	$a = array();
	$a['color'] = 'red';
	$a['taste'] = 'sweet';
	$a['shape'] = 'round';
	$a['name']  = 'apple';
	$a[]        = 4;        // la clave será 0

	$b = array();
	$b[] = 'a';
	$b[] = 'b';
	$b[] = 'c';

	// Después de que se ejecute el código, $a será el array
	// array('color' => 'red', 'taste' => 'sweet', 'shape' => 'round',
	// 'name' => 'apple', 0 => 4), y $b será el array
	// array(0 => 'a', 1 => 'b', 2 => 'c'), o simplemente array('a', 'b', 'c').
	?>

# BIBLIOGRAFIA

## https://ed.team/blog/cuales-son-los-lenguajes-de-programacion-mas-usados-de-2018

