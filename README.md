# glyffin-transfer

Transfer notation for glyffin entities.

All examples below assume a root element wraps the example.

	<glyffin-transfer>
		<example/>
	</glyffin-transfer>

## construction

### color

	<tile color="red" size="100x10"/>
	
### text

	<tile color="blue" text="Hello"/>
	
## modification

### pad
	<tile color="red" size="10"/>
	<pad amount="30"/>

### shift
	<tile color="red size="10"/>
	<shift amount="-20"/>

## aggregation

### extend

	<tile color="red" size="100x10"/>
	<extend edge="bottom" alignment=".5">
		<tile color="green" size="100x10"/>
	</extend>
	
### layer
	<tile color="red@10" size="10x10"/>
	<layer side="behind" alignment=".5x.5">
		<tile color="green" size="100x100"/>
	</layer>
	
