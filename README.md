# Demon-Summoning-Program
First project: A text based program based on the Shin Megami Tensei game series. You can negotiate with demons in order to progress. I plan to add 4 demons in total 
THIS PROGRAM RUNS IN JAVA

import java.util.*;
public class DSPV2 {

	public static void main(String[] args) {
		// começo
		System.out.println("                  ooo OOOAOOO ooo             ");		
		System.out.println("              oOO       / \\       OOo          ");
		System.out.println("          oOO          /   \\          OOo       ");
		System.out.println("       oOO            /     \\            OOo     ");
		System.out.println("     oOO             /       \\             OOo    ");
		System.out.println("   oOO -_-----------/---------\\-----------_- OOo   ");
		System.out.println("  oOO     -_       /           \\       _-     OOo   ");
		System.out.println(" oOO         -_   /             \\   _-         OOo  ");
		System.out.println("oOO             -/_             _\\-             OOo ");
		System.out.println("oOO             /  -_         _-  \\             OOo ");
		System.out.println("oOO            /      -_   _-      \\            OOo ");
		System.out.println("oOO           /         _-_         \\           OOo ");
		System.out.println("oOO          /       _-     -_       \\          OOo");
		System.out.println(" oOO        /     _-           -_     \\        OOo ");
		System.out.println("  oOO      /   _-                 -_   \\      OOo ");
		System.out.println("   oOO    / _-                       -_ \\    OOo ");
		System.out.println("     oOO _-                             -_ OOo   ");
		System.out.println("      oOO                                OOo  ");
		System.out.println("         oOO                         OOo      ");
		System.out.println("             oOO                 OOo       ");
		System.out.println("                 ooo OOO OOO ooo       ");
		System.out.println("             -----------------------");
		System.out.println("             DEMON SUMMONING PROGRAM");
		System.out.println("             ver. ALFA by: Blaze    ");
		System.out.println("                 COMP: 03.2022      ");
		System.out.println("             -----------------------");

		//versões futuras podem melhorar a interface do pentagrama
		System.out.println("INPUT DEMON NAME");
		Scanner In= new Scanner (System.in);
		String name, a;
		name= In.nextLine();
		if (name.equals("PIXIE")) {
		System.out.println("DEMON ACCEPTED");
	
		} else {
			System.out.println("ERROR TRY RESET");
			System.exit(0);
		} 
		//necessário pensar a respeito de caracteres maiusculos ou minusculos
		String race, b;
		System.out.println("INPUT DEMON RACE");
		race= In.nextLine();
		if (race.equals("FAIRY")) {
			System.out.println("FAIRY PIXIE");
			System.out.println("MAG COST= 50MAG");
		} else {
			System.out.println("RACE INCORRECT. RESET");
			System.exit(0);
		}
		String answersummon, c;
		System.out.println("SUMMON FAIRY PIXIE FOR 50 MAG?");
		answersummon= In.nextLine();
		if (answersummon.equals("yes")) {
			System.out.println("FAIRY PIXIE SUMMONED");
			System.out.println("FAIRY PIXIE: Hello Summoner! I'am Pixie the Fairy! Lets get this killing started!");
		}else {
			System.out.println("SUMMONING ENDED DEMON RETURNED");
			System.exit(0);
		}
		System.out.println("FAIRY PIXIE: Give me orders, summoner!");
		System.out.println("Give FAIRY PIXIE ORDERS");
		System.out.println("ORDERS: KILL, TALK, TRADE ITEM, BE MY DEMON");
		String orders, d;
		
		orders= In.nextLine();
		if (orders.equals("talk")) {
			System.out.println("FAIRY PIXIE: okay... What do you want to talk about then?");
			System.out.println("TALK ABOUT:");
			System.out.println("HUMANS? DEMONS? THINGS? LOVE? MONEY");
			String talk, f;
			talk= In.nextLine();
			if (talk.equals("humans")) {
				System.out.println("FAIRY PIXIE: Humans are funny creatures hihihihi, id love to split a  human head open to see what is inside! Can we do this, Mr. Summoner!?");
				System.out.println("INPUT ANSWER: YES//NO");
		
				String split, g;
				split=In.nextLine();
				//novamente diferenciando letras maiusculas, necessário checar isso em futuras versões
			if(split.equals("NO")) {
				System.out.println("FAIRY PIXIE: Awwwww, but how in hell can we know what's inside your head without opening it?");
				System.out.println("INPUT ANSWER: We have tools // We actually do it, but you cant do it to me // Go ahead and try your luck, fairy ");
				
			}else if (split.equals("YES")) {
				System.out.println("*BONK*");
				System.out.println("FAIRY PIXIE: Ouch... your head is hard!");
				System.out.println("FAIRY PIXIE: I will need compensation for that, Mr. Summoner!");
				
			}
			
			
			
			}
		}
		if (orders.equals("kill")) {
			System.out.println("FAIRY PIXIE: There's nothing to kill here summoner, are you dumb? hihihihi... I dont want a dumb summoner!");
			System.out.println("are you dumb?");
		String dumb, e;
		dumb= In.nextLine();
		if (dumb.equals("yes")) {
			System.out.println("FAIRY PIXIE: As i expected... well, im out.");
			System.out.println("PIXIE RAN AWAY");
			System.out.println("SUMMONING PROCESS ENDED RESET");
			System.exit(0);
		}
	
	
		}else if (orders.equals("no")) {
		
				System.out.println("FAIRY PIXIE: What? You summoned me all the way here for NOTHING? Stupid Summoner i should tear you apart for wasting my time");
				System.out.println("PIXIE RAN AWAY");
				System.out.println("OUT OF MAG SUMMONING PROCESS ENDED");
				System.exit(0);
			}
		
		}
	}
