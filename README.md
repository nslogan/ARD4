# ARD4

## Description

Optically-isolated 4-channel automotive relay driver (ARD). Intended for use in lab environment, robust and flexible driver with 1A output possible per channel. Jumper to select between active-high and active-low inputs, jumper to select between DB9 or external power for input side. Reverse-protection on both logic and relay side power. LED across relay driver output indicates if **relay** is getting power. Test points for logic and relay power, as well as one per channel on logic side. Board fits Sick of Beige DP8049 form factor (but should be used with 10mm stand-offs between board and top panel). You can find [this project on GitHub](https://github.com/nslogan/ARD4).

## Production

The board measures 3.15"x1.93" (80.01x49.02 mm) and was designed for production at [OSH Park](https://www.oshpark.com/). The OSHPark DRU is located in the `res/` folder.

The boards can be purchased [here](https://www.oshpark.com/shared_projects/R0TELkwq) @ $30.35 for three.

## Parts

All parts on this board are from the [LoganSmith-Eagle-Library](https://github.com/nslogan/LoganSmith-Eagle-Library) available on GitHub (work in progress).

The BOM is located in the release folder, all parts are sourced from Digi-Key.

## Project Structure

This project adheres to this structure:

	[ProjectName]
		README.md
		[release]
			[Major.Minor]
				ProjectName_BOM_Major.Minor.xls or ProjectName_BOM_BOM_Major.Minor.csv
				ProjectName_schematic_Major.Minor.pdf
				ProjectName_board-<top/mid#/bottom>_Major.Minor.png
				ProjectName_Major.Minor.sch
				ProjectName_Major.Minor.brd
				[Gerbers]
					...
			...
		[src]
			[Major.0]
				BoardName.sch
				BoardName.brd
				BOM.xls or BOM.csv
			[Major+1.0]
				...
			...
		[lib]
			...
		[res]
			Manufacturer.dru
			Manufacturer.cam