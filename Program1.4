/*****************************************************************************
Sarah Gilliland
CMPS 1044 - Halverson
Program 4 - Nlogonia Part 2
October 18, 2018
This program read coordinates from an input file and determines the country
where a given coordinate is located in the land of Nlogonia. It prints a
table with the coordinates and the corresponding location to an output file.
It is similar to Program 3, but has some updates.
*****************************************************************************/
#include <iostream>
#include <fstream>
#include <iomanip>

using namespace std;

int main()
{
	ofstream outputFile;
	outputFile.open("Output.txt");
	outputFile << "Sarah Gilliland\n\n\n";

	// Opening the input file that contains the location coordinates
	ifstream inputFile;
	int XCoor, YCoor;
	inputFile.open("NlogoniaData1.txt");

	// Reading the first location coordinates from the input file
	inputFile >> XCoor >> YCoor;

	outputFile << "The division point is " << XCoor << ", "
		<< YCoor << "\n";

	int NewXCoor, NewYCoor;
	char Location;
	// Looping so that all of the coordinants are read from the input file
	while (inputFile >> NewXCoor >> NewYCoor)
	{
		// Assigning the coordinates to their location on the map
		if (NewXCoor == XCoor && NewYCoor == YCoor)
		{
			Location = 'D';
		}
		else if (NewXCoor == XCoor || NewYCoor == YCoor)
		{
			if (NewXCoor == XCoor && NewYCoor > YCoor)
			{
				Location = 'W';
			}
			else if (NewXCoor == XCoor && NewYCoor < YCoor)
			{
				Location = 'Y';
			}
			else if (NewXCoor > XCoor && NewYCoor == YCoor)
			{
				Location = 'X';
			}
			else if (NewXCoor < XCoor && NewYCoor == YCoor)
			{
				Location = 'Z';
			}
		}
		else if (NewXCoor >= XCoor)
		{
			if (NewYCoor > YCoor) // Checking for Kiowa
			{
				Location = 'K';
			}
			else // Checking for Teepee
			{
				Location = 'T';
			}
		}
		else
		{
			if (NewYCoor > YCoor) // Checking for Comanche
			{
				Location = 'C';
			}
			else // Checking for Nocona
			{
				Location = 'N';
			}
		}
		// Switch statements to give the locations proper names
		switch (Location)
		{
		case 'D':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tDivision Point\n"; break;
		}
		case 'W':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tDividing line between Comanche and Kiowa\n"; break;
		}
		case 'Y':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tDividing line between Tepee and Nocona\n"; break;
		}
		case 'X':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tDividing line between Tepee and Kiowa\n"; break;
		}
		case 'Z':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tDividing line between Comanche and Nocona\n"; break;
		}
		case 'K':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tKiowa\n"; break;
		}
		case 'T':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tTeepee\n"; break;
		}
		case 'C':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tComanche\n"; break;
		}
		case 'N':
		{
			outputFile << setw(6) << NewXCoor << setw(6) << NewYCoor
				<< "\tNocona\n"; break;
		}
		}
	}
	// Closing the output and input files
	outputFile.close();
	inputFile.close();
	return 0;
}
