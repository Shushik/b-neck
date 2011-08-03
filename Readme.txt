
	CSS wrapper for guitar neck visualization


	Goods:

	— Easy to use;
	— Uses no images;
	— Works even in IE 6 and 7 (without the rounded corners
	  and some secondary stuff);
	— Different layouts for 2-8 stringed instruments;
	— Different layouts for bass instruments;
	— Full neck (12 frets) or partial neck (5 frets) layouts;
	— Display instrument tuning;
	— Display fingers numbers;
	— Display simple and barre chords layouts;
	— Display active/inactive strings.


	System requirements

	— Browser with CSS support;
	— Any HTML/CSS editor;
	— Basic HTML/CSS knowledges.


	Code examples


	 1. Link CSS files into HTML <head> section

	<code lang="html">
		<link rel="stylesheet" type="text/css" href="b-neck.css">
		<!--[if lt IE 8]>
			<link rel="stylesheet" type="text/css" href="b-neck.ie.css">
		<![endif]-->
	</code>


	 2. Link CSS files into project CSS file

	<code lang="css">
		/* For main CSS file *//**/
		@import "b-neck.css"
	</code>

	<code lang="css">
		/* For IE fix CSS file *//**/
		@import "b-neck.ie.css"
	</code>


	 3. Make the full guitar neck (12 frets)

	<code lang="html">
		<div class="b-neck">
			<div class="b-neck__fretboard SingleVI">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
					<div class="b-neck__fret VI"></div>
					<div class="b-neck__fret VII"></div>
					<div class="b-neck__fret VIII"></div>
					<div class="b-neck__fret IX"></div>
					<div class="b-neck__fret X"></div>
					<div class="b-neck__fret XI"></div>
					<div class="b-neck__fret XII"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   E"></div>
					<div class="b-neck__string II  H"></div>
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  E"></div>
				</div>
			</div>
		</div>
	</code>


	 4. Make the full bass guitar neck (12 frets)

	<code lang="html">
		<div class="b-neck">
			<div class="b-neck__fretboard BassIV">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
					<div class="b-neck__fret VI"></div>
					<div class="b-neck__fret VII"></div>
					<div class="b-neck__fret VIII"></div>
					<div class="b-neck__fret IX"></div>
					<div class="b-neck__fret X"></div>
					<div class="b-neck__fret XI"></div>
					<div class="b-neck__fret XII"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  E"></div>
				</div>
			</div>
		</div>
	</code>


	 5. Make the partial guitar neck (5 frets)

	<code lang="html">
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleVI">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   E"></div>
					<div class="b-neck__string II  H"></div>
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  E"></div>
				</div>
			</div>
		</div>
	</code>


	 6. Make the partial guitar neck (5 frets) with «Open D» tuning

	<code lang="html">
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleVI">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   D"></div>
					<div class="b-neck__string II  A"></div>
					<div class="b-neck__string III F♯"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  D"></div>
				</div>
			</div>
		</div>
	</code>


	 7. Make the partial 7 strings guitar neck (5 frets) with «Russian» tuning

	<code lang="html">
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleVII">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   D"></div>
					<div class="b-neck__string II  H"></div>
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   H"></div>
					<div class="b-neck__string VI  G"></div>
					<div class="b-neck__string VII D"></div>
				</div>
			</div>
		</div>
	</code>


	 8. Make the partial mandolin neck (5 frets)

	<code lang="html">
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleIV">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   E"></div>
					<div class="b-neck__string II  A"></div>
					<div class="b-neck__string III D"></div>
					<div class="b-neck__string IV  G"></div>
				</div>
			</div>
		</div>
	</code>


	 9. Make the simple chord (Am)

	<code>
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleVI">
				<div class="b-neck__frets">
					<div class="b-neck__fret Nut"></div>
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   E"></div>
					<div class="b-neck__string II  H"></div>
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  E"></div>
				</div>
			</div>

			<div class="b-neck__hand">
				<div class="b-neck__finger I   AtII  ToI"></div>
				<div class="b-neck__finger II  AtIII ToII"></div>
				<div class="b-neck__finger III AtIV  ToII"></div>
			</div>
		</div>
	</code>


	10. Make the barre chord (F♯m)

	<code>
		<div class="b-neck b-neck_type_part">
			<div class="b-neck__fretboard SingleVI">
				<div class="b-neck__frets">
					<div class="b-neck__fret I"></div>
					<div class="b-neck__fret II"></div>
					<div class="b-neck__fret III"></div>
					<div class="b-neck__fret IV"></div>
					<div class="b-neck__fret V"></div>
					<div class="b-neck__fret VI"></div>
				</div>

				<div class="b-neck__strings">
					<div class="b-neck__string I   E"></div>
					<div class="b-neck__string II  H"></div>
					<div class="b-neck__string III G"></div>
					<div class="b-neck__string IV  D"></div>
					<div class="b-neck__string V   A"></div>
					<div class="b-neck__string VI  E"></div>
				</div>

				<div class="b-neck__hand">
					<div class="b-neck__finger I   BarreVI"></div>
					<div class="b-neck__finger III AtIV ToIII"></div>
					<div class="b-neck__finger IV  AtV  ToIII"></div>
				</div>
			</div>
		</div>
	</code>
