# miniprogram

## [vars.scss](./vars.scss)

### example in taro / uni-app

```scss
@import '~@modyqyw/css-styles/miniprogram/vars.scss';

.container {
  color: $black;
}
```

### content

- Common Colors
  - `$black`: #000 <input type="color" value="#000000" disabled>
  - `$white`: #FFF <input type="color" value="#FFFFFF" disabled>
  - `$transparent`: transparent
- Material Design Colors
  - `$mdRed`: #F44336 <input type="color" value="#F44336" disabled> (error or danger)
  - `$mdRed50`: #FFEBEE <input type="color" value="#FFEBEE" disabled>
  - `$mdRed100`: #FFCDD2 <input type="color" value="#FFCDD2" disabled>
  - `$mdRed200`: #EF9A9A <input type="color" value="#EF9A9A" disabled>
  - `$mdRed300`: #E57373 <input type="color" value="#E57373" disabled>
  - `$mdRed400`: #EF5350 <input type="color" value="#EF5350" disabled>
  - `$mdRed500`: #F44336 <input type="color" value="#F44336" disabled> (error or danger)
  - `$mdRed600`: #E53935 <input type="color" value="#E53935" disabled>
  - `$mdRed700`: #D32F2F <input type="color" value="#D32F2F" disabled>
  - `$mdRed800`: #C62828 <input type="color" value="#C62828" disabled>
  - `$mdRed900`: #B71C1C <input type="color" value="#B71C1C" disabled>
  - `$mdRedA100`: #FF8A80 <input type="color" value="#FF8A80" disabled>
  - `$mdRedA200`: #FF5252 <input type="color" value="#FF5252" disabled>
  - `$mdRedA400`: #FF1744 <input type="color" value="#FF1744" disabled>
  - `$mdRedA700`: #D50000 <input type="color" value="#D50000" disabled>
  - `$mdPink`: #E91E63 <input type="color" value="#E91E63" disabled>
  - `$mdPink50`: #FCE4EC <input type="color" value="#FCE4EC" disabled>
  - `$mdPink100`: #F8BBD0 <input type="color" value="#F8BBD0" disabled>
  - `$mdPink200`: #F48FB1 <input type="color" value="#F48FB1" disabled>
  - `$mdPink300`: #F06292 <input type="color" value="#F06292" disabled>
  - `$mdPink400`: #EC407A <input type="color" value="#EC407A" disabled>
  - `$mdPink500`: #E91E63 <input type="color" value="#E91E63" disabled>
  - `$mdPink600`: #D81B60 <input type="color" value="#D81B60" disabled>
  - `$mdPink700`: #C2185B <input type="color" value="#C2185B" disabled>
  - `$mdPink800`: #AD1457 <input type="color" value="#AD1457" disabled>
  - `$mdPink900`: #880E4F <input type="color" value="#880E4F" disabled>
  - `$mdPinkA100`: #FF80AB <input type="color" value="#FF80AB" disabled>
  - `$mdPinkA200`: #FF4081 <input type="color" value="#FF4081" disabled>
  - `$mdPinkA400`: #F50057 <input type="color" value="#F50057" disabled>
  - `$mdPinkA700`: #C51162 <input type="color" value="#C51162" disabled>
  - `$mdPurple`: #9C27B0 <input type="color" value="#9C27B0" disabled>
  - `$mdPurple50`: #F3E5F5 <input type="color" value="#F3E5F5" disabled>
  - `$mdPurple100`: #E1BEE7 <input type="color" value="#E1BEE7" disabled>
  - `$mdPurple200`: #CE93D8 <input type="color" value="#CE93D8" disabled>
  - `$mdPurple300`: #BA68C8 <input type="color" value="#BA68C8" disabled>
  - `$mdPurple400`: #AB47BC <input type="color" value="#AB47BC" disabled>
  - `$mdPurple500`: #9C27B0 <input type="color" value="#9C27B0" disabled>
  - `$mdPurple600`: #8E24AA <input type="color" value="#8E24AA" disabled>
  - `$mdPurple700`: #7B1FA2 <input type="color" value="#7B1FA2" disabled>
  - `$mdPurple800`: #6A1B9A <input type="color" value="#6A1B9A" disabled>
  - `$mdPurple900`: #4A148C <input type="color" value="#4A148C" disabled>
  - `$mdPurpleA100`: #EA80FC <input type="color" value="#EA80FC" disabled>
  - `$mdPurpleA200`: #E040FB <input type="color" value="#E040FB" disabled>
  - `$mdPurpleA400`: #D500F9 <input type="color" value="#D500F9" disabled>
  - `$mdPurpleA700`: #A0F <input type="color" value="#AA00FF" disabled>
  - `$mdDeepPurple`: #673AB7 <input type="color" value="#673AB7" disabled>
  - `$mdDeepPurple50`: #EDE7F6 <input type="color" value="#EDE7F6" disabled>
  - `$mdDeepPurple100`: #D1C4E9 <input type="color" value="#D1C4E9" disabled>
  - `$mdDeepPurple200`: #B39DDB <input type="color" value="#B39DDB" disabled>
  - `$mdDeepPurple300`: #9575CD <input type="color" value="#9575CD" disabled>
  - `$mdDeepPurple400`: #7E57C2 <input type="color" value="#7E57C2" disabled>
  - `$mdDeepPurple500`: #673AB7 <input type="color" value="#673AB7" disabled>
  - `$mdDeepPurple600`: #5E35B1 <input type="color" value="#5E35B1" disabled>
  - `$mdDeepPurple700`: #512DA8 <input type="color" value="#512DA8" disabled>
  - `$mdDeepPurple800`: #4527A0 <input type="color" value="#4527A0" disabled>
  - `$mdDeepPurple900`: #311B92 <input type="color" value="#311B92" disabled>
  - `$mdDeepPurpleA100`: #B388FF <input type="color" value="#B388FF" disabled>
  - `$mdDeepPurpleA200`: #7C4DFF <input type="color" value="#7C4DFF" disabled>
  - `$mdDeepPurpleA400`: #651FFF <input type="color" value="#651FFF" disabled>
  - `$mdDeepPurpleA700`: #6200EA <input type="color" value="#6200EA" disabled>
  - `$mdIndigo`: #3F51B5 <input type="color" value="#3F51B5" disabled>
  - `$mdIndigo50`: #E8EAF6 <input type="color" value="#E8EAF6" disabled>
  - `$mdIndigo100`: #C5CAE9 <input type="color" value="#C5CAE9" disabled>
  - `$mdIndigo200`: #9FA8DA <input type="color" value="#9FA8DA" disabled>
  - `$mdIndigo300`: #7986CB <input type="color" value="#7986CB" disabled>
  - `$mdIndigo400`: #5C6BC0 <input type="color" value="#5C6BC0" disabled>
  - `$mdIndigo500`: #3F51B5 <input type="color" value="#3F51B5" disabled>
  - `$mdIndigo600`: #3949AB <input type="color" value="#3949AB" disabled>
  - `$mdIndigo700`: #303F9F <input type="color" value="#303F9F" disabled>
  - `$mdIndigo800`: #283593 <input type="color" value="#283593" disabled>
  - `$mdIndigo900`: #1A237E <input type="color" value="#1A237E" disabled>
  - `$mdIndigoA100`: #8C9EFF <input type="color" value="#8C9EFF" disabled>
  - `$mdIndigoA200`: #536DFE <input type="color" value="#536DFE" disabled>
  - `$mdIndigoA400`: #3D5AFE <input type="color" value="#3D5AFE" disabled>
  - `$mdIndigoA700`: #304FFE <input type="color" value="#304FFE" disabled>
  - `$mdBlue`: #2196F3 <input type="color" value="#2196F3" disabled> (primary)
  - `$mdBlue50`: #E3F2FD <input type="color" value="#E3F2FD" disabled>
  - `$mdBlue100`: #BBDEFB <input type="color" value="#BBDEFB" disabled>
  - `$mdBlue200`: #90CAF9 <input type="color" value="#90CAF9" disabled>
  - `$mdBlue300`: #64B5F6 <input type="color" value="#64B5F6" disabled>
  - `$mdBlue400`: #42A5F5 <input type="color" value="#42A5F5" disabled>
  - `$mdBlue500`: #2196F3 <input type="color" value="#2196F3" disabled> (primary)
  - `$mdBlue600`: #1E88E5 <input type="color" value="#1E88E5" disabled>
  - `$mdBlue700`: #1976D2 <input type="color" value="#1976D2" disabled>
  - `$mdBlue800`: #1565C0 <input type="color" value="#1565C0" disabled>
  - `$mdBlue900`: #0D47A1 <input type="color" value="#0D47A1" disabled>
  - `$mdBlueA100`: #82B1FF <input type="color" value="#82B1FF" disabled>
  - `$mdBlueA200`: #448AFF <input type="color" value="#448AFF" disabled>
  - `$mdBlueA400`: #2979FF <input type="color" value="#2979FF" disabled>
  - `$mdblueA700`: #2962FF <input type="color" value="#2962FF" disabled>
  - `$mdLightBlue`: #03A9F4 <input type="color" value="#03A9F4" disabled>
  - `$mdLightBlue50`: #E1F5FE <input type="color" value="#E1F5FE" disabled>
  - `$mdLightBlue100`: #B3E5FC <input type="color" value="#B3E5FC" disabled>
  - `$mdLightBlue200`: #81D4FA <input type="color" value="#81D4FA" disabled>
  - `$mdLightBlue300`: #4FC3F7 <input type="color" value="#4FC3F7" disabled>
  - `$mdLightBlue400`: #29B6F6 <input type="color" value="#29B6F6" disabled>
  - `$mdLightBlue500`: #03A9F4 <input type="color" value="#03A9F4" disabled>
  - `$mdLightBlue600`: #039BE5 <input type="color" value="#039BE5" disabled>
  - `$mdLightBlue700`: #0288D1 <input type="color" value="#0288D1" disabled>
  - `$mdLightBlue800`: #0277BD <input type="color" value="#0277BD" disabled>
  - `$mdLightBlue900`: #01579B <input type="color" value="#01579B" disabled>
  - `$mdLightBlueA100`: #80D8FF <input type="color" value="#80D8FF" disabled>
  - `$mdLightBlueA200`: #40C4FF <input type="color" value="#40C4FF" disabled>
  - `$mdLightBlueA400`: #00B0FF <input type="color" value="#00B0FF" disabled>
  - `$mdLightBlueA700`: #0091EA <input type="color" value="#0091EA" disabled>
  - `$mdCyan`: #00BCD4 <input type="color" value="#00BCD4" disabled>
  - `$mdCyan50`: #E0F7FA <input type="color" value="#E0F7FA" disabled>
  - `$mdCyan100`: #B2EBF2 <input type="color" value="#B2EBF2" disabled>
  - `$mdCyan200`: #80DEEA <input type="color" value="#80DEEA" disabled>
  - `$mdCyan300`: #4DD0E1 <input type="color" value="#4DD0E1" disabled>
  - `$mdCyan400`: #26C6DA <input type="color" value="#26C6DA" disabled>
  - `$mdCyan500`: #00BCD4 <input type="color" value="#00BCD4" disabled>
  - `$mdCyan600`: #00ACC1 <input type="color" value="#00ACC1" disabled>
  - `$mdCyan700`: #0097A7 <input type="color" value="#0097A7" disabled>
  - `$mdCyan800`: #00838F <input type="color" value="#00838F" disabled>
  - `$mdCyan900`: #006064 <input type="color" value="#006064" disabled>
  - `$mdCyanA100`: #84FFFF <input type="color" value="#84FFFF" disabled>
  - `$mdCyanA200`: #18FFFF <input type="color" value="#18FFFF" disabled>
  - `$mdCyanA400`: #00E5FF <input type="color" value="#00E5FF" disabled>
  - `$mdCyanA700`: #00B8D4 <input type="color" value="#00B8D4" disabled>
  - `$mdTeal`: #009688 <input type="color" value="#009688" disabled>
  - `$mdTeal50`: #E0F2F1 <input type="color" value="#E0F2F1" disabled>
  - `$mdTeal100`: #B2DFDB <input type="color" value="#B2DFDB" disabled>
  - `$mdTeal200`: #80CBC4 <input type="color" value="#80CBC4" disabled>
  - `$mdTeal300`: #4DB6AC <input type="color" value="#4DB6AC" disabled>
  - `$mdTeal400`: #26A69A <input type="color" value="#26A69A" disabled>
  - `$mdTeal500`: #009688 <input type="color" value="#009688" disabled>
  - `$mdTeal600`: #00897B <input type="color" value="#00897B" disabled>
  - `$mdTeal700`: #00796B <input type="color" value="#00796B" disabled>
  - `$mdTeal800`: #00695C <input type="color" value="#00695C" disabled>
  - `$mdTeal900`: #004D40 <input type="color" value="#004D40" disabled>
  - `$mdTealA100`: #A7FFEB <input type="color" value="#A7FFEB" disabled>
  - `$mdTealA200`: #64FFDA <input type="color" value="#64FFDA" disabled>
  - `$mdTealA400`: #1DE9B6 <input type="color" value="#1DE9B6" disabled>
  - `$mdTealA700`: #00BFA5 <input type="color" value="#00BFA5" disabled>
  - `$mdGreen`: #4CAF50 <input type="color" value="#4CAF50" disabled> (success)
  - `$mdGreen50`: #E8F5E9 <input type="color" value="#E8F5E9" disabled>
  - `$mdGreen100`: #C8E6C9 <input type="color" value="#C8E6C9" disabled>
  - `$mdGreen200`: #A5D6A7 <input type="color" value="#A5D6A7" disabled>
  - `$mdGreen300`: #81C784 <input type="color" value="#81C784" disabled>
  - `$mdGreen400`: #66BB6A <input type="color" value="#66BB6A" disabled>
  - `$mdGreen500`: #4CAF50 <input type="color" value="#4CAF50" disabled> (success)
  - `$mdGreen600`: #43A047 <input type="color" value="#43A047" disabled>
  - `$mdGreen700`: #388E3C <input type="color" value="#388E3C" disabled>
  - `$mdGreen800`: #2E7D32 <input type="color" value="#2E7D32" disabled>
  - `$mdGreen900`: #1B5E20 <input type="color" value="#1B5E20" disabled>
  - `$mdGreenA100`: #B9F6CA <input type="color" value="#B9F6CA" disabled>
  - `$mdGreenA200`: #69F0AE <input type="color" value="#69F0AE" disabled>
  - `$mdGreenA400`: #00E676 <input type="color" value="#00E676" disabled>
  - `$mdGreenA700`: #00C853 <input type="color" value="#00C853" disabled>
  - `$mdLightGreen`: #8BC34A <input type="color" value="#8BC34A" disabled>
  - `$mdLightGreen50`: #F1F8E9 <input type="color" value="#F1F8E9" disabled>
  - `$mdLightGreen100`: #DCEDC8 <input type="color" value="#DCEDC8" disabled>
  - `$mdLightGreen200`: #C5E1A5 <input type="color" value="#C5E1A5" disabled>
  - `$mdLightGreen300`: #AED581 <input type="color" value="#AED581" disabled>
  - `$mdLightGreen400`: #9CCC65 <input type="color" value="#9CCC65" disabled>
  - `$mdLightGreen500`: #8BC34A <input type="color" value="#8BC34A" disabled>
  - `$mdLightGreen600`: #7CB342 <input type="color" value="#7CB342" disabled>
  - `$mdLightGreen700`: #689F38 <input type="color" value="#689F38" disabled>
  - `$mdLightGreen800`: #558B2F <input type="color" value="#558B2F" disabled>
  - `$mdLightGreen900`: #33691E <input type="color" value="#33691E" disabled>
  - `$mdLightGreenA100`: #CCFF90 <input type="color" value="#CCFF90" disabled>
  - `$mdLightGreenA200`: #B2FF59 <input type="color" value="#B2FF59" disabled>
  - `$mdLightGreenA400`: #76FF03 <input type="color" value="#76FF03" disabled>
  - `$mdLightGreenA700`: #64DD17 <input type="color" value="#64DD17" disabled>
  - `$mdLime`: #CDDC39 <input type="color" value="#CDDC39" disabled>
  - `$mdLime50`: #F9FBE7 <input type="color" value="#F9FBE7" disabled>
  - `$mdLime100`: #F0F4C3 <input type="color" value="#F0F4C3" disabled>
  - `$mdLime200`: #E6EE9C <input type="color" value="#E6EE9C" disabled>
  - `$mdLime300`: #DCE775 <input type="color" value="#DCE775" disabled>
  - `$mdLime400`: #D4E157 <input type="color" value="#D4E157" disabled>
  - `$mdLime500`: #CDDC39 <input type="color" value="#CDDC39" disabled>
  - `$mdLime600`: #C0CA33 <input type="color" value="#C0CA33" disabled>
  - `$mdLime700`: #AFB42B <input type="color" value="#AFB42B" disabled>
  - `$mdLime800`: #9E9D24 <input type="color" value="#9E9D24" disabled>
  - `$mdLime900`: #827717 <input type="color" value="#827717" disabled>
  - `$mdLimeA100`: #F4FF81 <input type="color" value="#F4FF81" disabled>
  - `$mdLimeA200`: #EEFF41 <input type="color" value="#EEFF41" disabled>
  - `$mdLimeA400`: #C6FF00 <input type="color" value="#C6FF00" disabled>
  - `$mdLimeA700`: #AEEA00 <input type="color" value="#AEEA00" disabled>
  - `$mdYellow`: #FFEB3B <input type="color" value="#FFEB3B" disabled> (warning)
  - `$mdYellow50`: #FFFDE7 <input type="color" value="#FFFDE7" disabled>
  - `$mdYellow100`: #FFF9C4 <input type="color" value="#FFF9C4" disabled>
  - `$mdYellow200`: #FFF59D <input type="color" value="#FFF59D" disabled>
  - `$mdYellow300`: #FFF176 <input type="color" value="#FFF176" disabled>
  - `$mdYellow400`: #FFEE58 <input type="color" value="#FFEE58" disabled>
  - `$mdYellow500`: #FFEB3B <input type="color" value="#FFEB3B" disabled> (warning)
  - `$mdYellow600`: #FDD835 <input type="color" value="#FDD835" disabled>
  - `$mdYellow700`: #FBC02D <input type="color" value="#FBC02D" disabled>
  - `$mdYellow800`: #F9A825 <input type="color" value="#F9A825" disabled>
  - `$mdYellow900`: #F57F17 <input type="color" value="#F57F17" disabled>
  - `$mdYellowA100`: #FFFF8D <input type="color" value="#FFFF8D" disabled>
  - `$mdYellowA200`: #FF0 <input type="color" value="#FFFF00" disabled>
  - `$mdYellowA400`: #FFEA00 <input type="color" value="#FFEA00" disabled>
  - `$mdYellowA700`: #FFD600 <input type="color" value="#FFD600" disabled>
  - `$mdAmber`: #FFC107 <input type="color" value="#FFC107" disabled>
  - `$mdAmber50`: #FFF8E1 <input type="color" value="#FFF8E1" disabled>
  - `$mdAmber100`: #FFECB3 <input type="color" value="#FFECB3" disabled>
  - `$mdAmber200`: #FFE082 <input type="color" value="#FFE082" disabled>
  - `$mdAmber300`: #FFD54F <input type="color" value="#FFD54F" disabled>
  - `$mdAmber400`: #FFCA28 <input type="color" value="#FFCA28" disabled>
  - `$mdAmber500`: #FFC107 <input type="color" value="#FFC107" disabled>
  - `$mdAmber600`: #FFB300 <input type="color" value="#FFB300" disabled>
  - `$mdAmber700`: #FFA000 <input type="color" value="#FFA000" disabled>
  - `$mdAmber800`: #FF8F00 <input type="color" value="#FF8F00" disabled>
  - `$mdAmber900`: #FF6F00 <input type="color" value="#FF6F00" disabled>
  - `$mdAmberA100`: #FFE57F <input type="color" value="#FFE57F" disabled>
  - `$mdAmberA200`: #FFD740 <input type="color" value="#FFD740" disabled>
  - `$mdAmberA400`: #FFC400 <input type="color" value="#FFC400" disabled>
  - `$mdAmberA700`: #FFAB00 <input type="color" value="#FFAB00" disabled>
  - `$mdOrange`: #FF9800 <input type="color" value="#FF9800" disabled>
  - `$mdOrange50`: #FFF3E0 <input type="color" value="#FFF3E0" disabled>
  - `$mdOrange100`: #FFE0B2 <input type="color" value="#FFE0B2" disabled>
  - `$mdOrange200`: #FFCC80 <input type="color" value="#FFCC80" disabled>
  - `$mdOrange300`: #FFB74D <input type="color" value="#FFB74D" disabled>
  - `$mdOrange400`: #FFA726 <input type="color" value="#FFA726" disabled>
  - `$mdOrange500`: #FF9800 <input type="color" value="#FF9800" disabled>
  - `$mdOrange600`: #FB8C00 <input type="color" value="#FB8C00" disabled>
  - `$mdOrange700`: #F57C00 <input type="color" value="#F57C00" disabled>
  - `$mdOrange800`: #EF6C00 <input type="color" value="#EF6C00" disabled>
  - `$mdOrange900`: #E65100 <input type="color" value="#E65100" disabled>
  - `$mdOrangeA100`: #FFD180 <input type="color" value="#FFD180" disabled>
  - `$mdOrangeA200`: #FFAB40 <input type="color" value="#FFAB40" disabled>
  - `$mdOrangeA400`: #FF9100 <input type="color" value="#FF9100" disabled>
  - `$mdOrangeA700`: #FF6D00 <input type="color" value="#FF6D00" disabled>
  - `$mdDeepOrange`: #FF5722 <input type="color" value="#FF5722" disabled>
  - `$mdDeepOrange50`: #FBE9E7 <input type="color" value="#FBE9E7" disabled>
  - `$mdDeepOrange100`: #FFCCBC <input type="color" value="#FFCCBC" disabled>
  - `$mdDeepOrange200`: #FFAB91 <input type="color" value="#FFAB91" disabled>
  - `$mdDeepOrange300`: #FF8A65 <input type="color" value="#FF8A65" disabled>
  - `$mdDeepOrange400`: #FF7043 <input type="color" value="#FF7043" disabled>
  - `$mdDeepOrange500`: #FF5722 <input type="color" value="#FF5722" disabled>
  - `$mdDeepOrange600`: #F4511E <input type="color" value="#F4511E" disabled>
  - `$mdDeepOrange700`: #E64A19 <input type="color" value="#E64A19" disabled>
  - `$mdDeepOrange800`: #D84315 <input type="color" value="#D84315" disabled>
  - `$mdDeepOrange900`: #BF360C <input type="color" value="#BF360C" disabled>
  - `$mdDeepOrangeA100`: #FF9E80 <input type="color" value="#FF9E80" disabled>
  - `$mdDeepOrangeA200`: #FF6E40 <input type="color" value="#FF6E40" disabled>
  - `$mdDeepOrangeA400`: #FF3D00 <input type="color" value="#FF3D00" disabled>
  - `$mdDeepOrangeA700`: #DD2C00 <input type="color" value="#DD2C00" disabled>
  - `$mdBrown`: #795548 <input type="color" value="#795548" disabled>
  - `$mdBrown50`: #EFEBE9 <input type="color" value="#EFEBE9" disabled>
  - `$mdBrown100`: #D7CCC8 <input type="color" value="#D7CCC8" disabled>
  - `$mdBrown200`: #BCAAA4 <input type="color" value="#BCAAA4" disabled>
  - `$mdBrown300`: #A1887F <input type="color" value="#A1887F" disabled>
  - `$mdBrown400`: #8D6E63 <input type="color" value="#8D6E63" disabled>
  - `$mdBrown500`: #795548 <input type="color" value="#795548" disabled>
  - `$mdBrown600`: #6D4C41 <input type="color" value="#6D4C41" disabled>
  - `$mdBrown700`: #5D4037 <input type="color" value="#5D4037" disabled>
  - `$mdBrown800`: #4E342E <input type="color" value="#4E342E" disabled>
  - `$mdBrown900`: #3E2723 <input type="color" value="#3E2723" disabled>
  - `$mdGray`: #9E9E9E <input type="color" value="#9E9E9E" disabled>
  - `$mdGray50`: #FAFAFA <input type="color" value="#FAFAFA" disabled>
  - `$mdGray100`: #F5F5F5 <input type="color" value="#F5F5F5" disabled>
  - `$mdGray200`: #EEE <input type="color" value="#EEEEEE" disabled>
  - `$mdGray300`: #E0E0E0 <input type="color" value="#E0E0E0" disabled>
  - `$mdGray400`: #BDBDBD <input type="color" value="#BDBDBD" disabled>
  - `$mdGray500`: #9E9E9E <input type="color" value="#9E9E9E" disabled>
  - `$mdGray600`: #757575 <input type="color" value="#757575" disabled>
  - `$mdGray700`: #616161 <input type="color" value="#616161" disabled>
  - `$mdGray800`: #424242 <input type="color" value="#424242" disabled>
  - `$mdGray900`: #212121 <input type="color" value="#212121" disabled>
  - `$mdBlueGray`: #607D8B <input type="color" value="#607D8B" disabled>
  - `$mdBlueGray50`: #ECEFF1 <input type="color" value="#ECEFF1" disabled>
  - `$mdBlueGray100`: #CFD8DC <input type="color" value="#CFD8DC" disabled>
  - `$mdBlueGray200`: #B0BEC5 <input type="color" value="#B0BEC5" disabled>
  - `$mdBlueGray300`: #90A4AE <input type="color" value="#90A4AE" disabled>
  - `$mdBlueGray400`: #78909C <input type="color" value="#78909C" disabled>
  - `$mdBlueGray500`: #607D8B <input type="color" value="#607D8B" disabled>
  - `$mdBlueGray600`: #546E7A <input type="color" value="#546E7A" disabled>
  - `$mdBlueGray700`: #455A64 <input type="color" value="#455A64" disabled>
  - `$mdBlueGray800`: #37474F <input type="color" value="#37474F" disabled>
  - `$mdBlueGray900`: #263238 <input type="color" value="#263238" disabled>
  - `$mdGrey`: #9E9E9E <input type="color" value="#9E9E9E" disabled>
  - `$mdGrey50`: #FAFAFA <input type="color" value="#FAFAFA" disabled>
  - `$mdGrey100`: #F5F5F5 <input type="color" value="#F5F5F5" disabled>
  - `$mdGrey200`: #EEE <input type="color" value="#EEEEEE" disabled>
  - `$mdGrey300`: #E0E0E0 <input type="color" value="#E0E0E0" disabled>
  - `$mdGrey400`: #BDBDBD <input type="color" value="#BDBDBD" disabled>
  - `$mdGrey500`: #9E9E9E <input type="color" value="#9E9E9E" disabled>
  - `$mdGrey600`: #757575 <input type="color" value="#757575" disabled>
  - `$mdGrey700`: #616161 <input type="color" value="#616161" disabled>
  - `$mdGrey800`: #424242 <input type="color" value="#424242" disabled>
  - `$mdGrey900`: #212121 <input type="color" value="#212121" disabled>
  - `$mdBlueGrey`: #607D8B <input type="color" value="#607D8B" disabled>
  - `$mdBlueGrey50`: #ECEFF1 <input type="color" value="#ECEFF1" disabled>
  - `$mdBlueGrey100`: #CFD8DC <input type="color" value="#CFD8DC" disabled>
  - `$mdBlueGrey200`: #B0BEC5 <input type="color" value="#B0BEC5" disabled>
  - `$mdBlueGrey300`: #90A4AE <input type="color" value="#90A4AE" disabled>
  - `$mdBlueGrey400`: #78909C <input type="color" value="#78909C" disabled>
  - `$mdBlueGrey500`: #607D8B <input type="color" value="#607D8B" disabled>
  - `$mdBlueGrey600`: #546E7A <input type="color" value="#546E7A" disabled>
  - `$mdBlueGrey700`: #455A64 <input type="color" value="#455A64" disabled>
  - `$mdBlueGrey800`: #37474F <input type="color" value="#37474F" disabled>
  - `$mdBlueGrey900`: #263238 <input type="color" value="#263238" disabled>
- Ant Design Colors
  - `$adRed`: #F5222D <input type="color" value="#F5222D" disabled> (error / danger)
  - `$adRed1`: #FFF1F0 <input type="color" value="#FFF1F0" disabled>
  - `$adRed2`: #FFCCC7 <input type="color" value="#FFCCC7" disabled>
  - `$adRed3`: #FFA39E <input type="color" value="#FFA39E" disabled>
  - `$adRed4`: #FF7875 <input type="color" value="#FF7875" disabled>
  - `$adRed5`: #FF4D4F <input type="color" value="#FF4D4F" disabled>
  - `$adRed6`: #F5222D <input type="color" value="#F5222D" disabled> (error / danger)
  - `$adRed7`: #CF1322 <input type="color" value="#CF1322" disabled>
  - `$adRed8`: #A8071A <input type="color" value="#A8071A" disabled>
  - `$adRed9`: #820014 <input type="color" value="#820014" disabled>
  - `$adRed10`: #5C0011 <input type="color" value="#5C0011" disabled>
  - `$adVolcano`: #FF7A45 <input type="color" value="#FF7A45" disabled>
  - `$adVolcano1`: #FFF2E8 <input type="color" value="#FFF2E8" disabled>
  - `$adVolcano2`: #FFD8BF <input type="color" value="#FFD8BF" disabled>
  - `$adVolcano3`: #FFBB96 <input type="color" value="#FFBB96" disabled>
  - `$adVolcano4`: #FF9C6E <input type="color" value="#FF9C6E" disabled>
  - `$adVolcano5`: #FF7A45 <input type="color" value="#FF7A45" disabled>
  - `$adVolcano6`: #FA541C <input type="color" value="#FA541C" disabled>
  - `$adVolcano7`: #D4380D <input type="color" value="#D4380D" disabled>
  - `$adVolcano8`: #AD2102 <input type="color" value="#AD2102" disabled>
  - `$adVolcano9`: #871400 <input type="color" value="#871400" disabled>
  - `$adVolcano10`: #610B00 <input type="color" value="#610B00" disabled>
  - `$adOrange`: #FA8C16 <input type="color" value="#FA8C16" disabled>
  - `$adOrange1`: #FFF7E6 <input type="color" value="#FFF7E6" disabled>
  - `$adOrange2`: #FFE7BA <input type="color" value="#FFE7BA" disabled>
  - `$adOrange3`: #FFD591 <input type="color" value="#FFD591" disabled>
  - `$adOrange4`: #FFC069 <input type="color" value="#FFC069" disabled>
  - `$adOrange5`: #FFA940 <input type="color" value="#FFA940" disabled>
  - `$adOrange6`: #FA8C16 <input type="color" value="#FA8C16" disabled>
  - `$adOrange7`: #D46B08 <input type="color" value="#D46B08" disabled>
  - `$adOrange8`: #AD4E00 <input type="color" value="#AD4E00" disabled>
  - `$adOrange9`: #873800 <input type="color" value="#873800" disabled>
  - `$adOrange10`: #612500 <input type="color" value="#612500" disabled>
  - `$adGold`: #FAAD14 <input type="color" value="#FAAD14" disabled> (warning)
  - `$adGold1`: #FFFBE6 <input type="color" value="#FFFBE6" disabled>
  - `$adGold2`: #FFF1B8 <input type="color" value="#FFF1B8" disabled>
  - `$adGold3`: #FFE58F <input type="color" value="#FFE58F" disabled>
  - `$adGold4`: #FFD666 <input type="color" value="#FFD666" disabled>
  - `$adGold5`: #FFC53D <input type="color" value="#FFC53D" disabled>
  - `$adGold6`: #FAAD14 <input type="color" value="#FAAD14" disabled> (warning)
  - `$adGold7`: #D48806 <input type="color" value="#D48806" disabled>
  - `$adGold8`: #AD6800 <input type="color" value="#AD6800" disabled>
  - `$adGold9`: #874D00 <input type="color" value="#874D00" disabled>
  - `$adGold10`: #613400 <input type="color" value="#613400" disabled>
  - `$adYellow`: #FADB14 <input type="color" value="#FADB14" disabled>
  - `$adYellow1`: #FEFFE6 <input type="color" value="#FEFFE6" disabled>
  - `$adYellow2`: #FFFFB8 <input type="color" value="#FFFFB8" disabled>
  - `$adYellow3`: #FFFB8F <input type="color" value="#FFFB8F" disabled>
  - `$adYellow4`: #FFF566 <input type="color" value="#FFF566" disabled>
  - `$adYellow5`: #FFEC3D <input type="color" value="#FFEC3D" disabled>
  - `$adYellow6`: #FADB14 <input type="color" value="#FADB14" disabled>
  - `$adYellow7`: #D4B106 <input type="color" value="#D4B106" disabled>
  - `$adYellow8`: #AD8B00 <input type="color" value="#AD8B00" disabled>
  - `$adYellow9`: #876800 <input type="color" value="#876800" disabled>
  - `$adYellow10`: #614700 <input type="color" value="#614700" disabled>
  - `$adLime`: #A0D911 <input type="color" value="#A0D911" disabled>
  - `$adLime1`: #FCFFE6 <input type="color" value="#FCFFE6" disabled>
  - `$adLime2`: #F4FFB8 <input type="color" value="#F4FFB8" disabled>
  - `$adLime3`: #EAFF8F <input type="color" value="#EAFF8F" disabled>
  - `$adLime4`: #D3F261 <input type="color" value="#D3F261" disabled>
  - `$adLime5`: #BAE637 <input type="color" value="#BAE637" disabled>
  - `$adLime6`: #A0D911 <input type="color" value="#A0D911" disabled>
  - `$adLime7`: #7CB305 <input type="color" value="#7CB305" disabled>
  - `$adLime8`: #5B8C00 <input type="color" value="#5B8C00" disabled>
  - `$adLime9`: #3F6600 <input type="color" value="#3F6600" disabled>
  - `$adLime10`: #254000 <input type="color" value="#254000" disabled>
  - `$adGreen`: #52C41A <input type="color" value="#52C41A" disabled> (success)
  - `$adGreen1`: #F6FFED <input type="color" value="#F6FFED" disabled>
  - `$adGreen2`: #D9F7BE <input type="color" value="#D9F7BE" disabled>
  - `$adGreen3`: #B7EB8F <input type="color" value="#B7EB8F" disabled>
  - `$adGreen4`: #95DE64 <input type="color" value="#95DE64" disabled>
  - `$adGreen5`: #73D13D <input type="color" value="#73D13D" disabled>
  - `$adGreen6`: #52C41A <input type="color" value="#52C41A" disabled> (success)
  - `$adGreen7`: #389E0D <input type="color" value="#389E0D" disabled>
  - `$adGreen8`: #237804 <input type="color" value="#237804" disabled>
  - `$adGreen9`: #135200 <input type="color" value="#135200" disabled>
  - `$adGreen10`: #092B00 <input type="color" value="#092B00" disabled>
  - `$adCyan`: #13C2C2 <input type="color" value="#13C2C2" disabled>
  - `$adCyan1`: #E6FFFB <input type="color" value="#E6FFFB" disabled>
  - `$adCyan2`: #B5F5EC <input type="color" value="#B5F5EC" disabled>
  - `$adCyan3`: #87E8DE <input type="color" value="#87E8DE" disabled>
  - `$adCyan4`: #5CDBD3 <input type="color" value="#5CDBD3" disabled>
  - `$adCyan5`: #36CFC9 <input type="color" value="#36CFC9" disabled>
  - `$adCyan6`: #13C2C2 <input type="color" value="#13C2C2" disabled>
  - `$adCyan7`: #08979C <input type="color" value="#08979C" disabled>
  - `$adCyan8`: #006D75 <input type="color" value="#006D75" disabled>
  - `$adCyan9`: #00474F <input type="color" value="#00474F" disabled>
  - `$adCyan10`: #002329 <input type="color" value="#002329" disabled>
  - `$adBlue`: #1890FF <input type="color" value="#1890FF" disabled> (primary)
  - `$adBlue1`: #E6F7FF <input type="color" value="#E6F7FF" disabled>
  - `$adBlue2`: #BAE7FF <input type="color" value="#BAE7FF" disabled>
  - `$adBlue3`: #91D5FF <input type="color" value="#91D5FF" disabled>
  - `$adBlue4`: #69C0FF <input type="color" value="#69C0FF" disabled>
  - `$adBlue5`: #40A9FF <input type="color" value="#40A9FF" disabled>
  - `$adBlue6`: #1890FF <input type="color" value="#1890FF" disabled> (primary)
  - `$adBlue7`: #096DD9 <input type="color" value="#096DD9" disabled>
  - `$adBlue8`: #0050B3 <input type="color" value="#0050B3" disabled>
  - `$adBlue9`: #003A8C <input type="color" value="#003A8C" disabled>
  - `$adBlue10`: #002766 <input type="color" value="#002766" disabled>
  - `$adGeekBlue`: #2F54EB <input type="color" value="#2F54EB" disabled>
  - `$adGeekBlue1`: #F0F5FF <input type="color" value="#F0F5FF" disabled>
  - `$adGeekBlue2`: #D6E4FF <input type="color" value="#D6E4FF" disabled>
  - `$adGeekBlue3`: #ADC6FF <input type="color" value="#ADC6FF" disabled>
  - `$adGeekBlue4`: #85A5FF <input type="color" value="#85A5FF" disabled>
  - `$adGeekBlue5`: #597EF7 <input type="color" value="#597EF7" disabled>
  - `$adGeekBlue6`: #2F54EB <input type="color" value="#2F54EB" disabled>
  - `$adGeekBlue7`: #1D39C4 <input type="color" value="#1D39C4" disabled>
  - `$adGeekBlue8`: #10239E <input type="color" value="#10239E" disabled>
  - `$adGeekBlue9`: #061178 <input type="color" value="#061178" disabled>
  - `$adGeekBlue10`: #030852 <input type="color" value="#030852" disabled>
  - `$adPurple`: #722ED1 <input type="color" value="#722ED1" disabled>
  - `$adPurple1`: #F9F0FF <input type="color" value="#F9F0FF" disabled>
  - `$adPurple2`: #EFDBFF <input type="color" value="#EFDBFF" disabled>
  - `$adPurple3`: #D3ADF7 <input type="color" value="#D3ADF7" disabled>
  - `$adPurple4`: #B37FEB <input type="color" value="#B37FEB" disabled>
  - `$adPurple5`: #9254DE <input type="color" value="#9254DE" disabled>
  - `$adPurple6`: #722ED1 <input type="color" value="#722ED1" disabled>
  - `$adPurple7`: #531DAB <input type="color" value="#531DAB" disabled>
  - `$adPurple8`: #391085 <input type="color" value="#391085" disabled>
  - `$adPurple9`: #22075E <input type="color" value="#22075E" disabled>
  - `$adPurple10`: #120338 <input type="color" value="#120338" disabled>
  - `$adMagenta`: #EB2F96 <input type="color" value="#EB2F96" disabled>
  - `$adMagenta1`: #FFF0F6 <input type="color" value="#FFF0F6" disabled>
  - `$adMagenta2`: #FFD6E7 <input type="color" value="#FFD6E7" disabled>
  - `$adMagenta3`: #FFADD2 <input type="color" value="#FFADD2" disabled>
  - `$adMagenta4`: #FF85C0 <input type="color" value="#FF85C0" disabled>
  - `$adMagenta5`: #F759AB <input type="color" value="#F759AB" disabled>
  - `$adMagenta6`: #EB2F96 <input type="color" value="#EB2F96" disabled>
  - `$adMagenta7`: #C41D7F <input type="color" value="#C41D7F" disabled>
  - `$adMagenta8`: #9E1068 <input type="color" value="#9E1068" disabled>
  - `$adMagenta9`: #780650 <input type="color" value="#780650" disabled>
  - `$adMagenta10`: #520339 <input type="color" value="#520339" disabled>
  - `$adGray`: #BFBFBF <input type="color" value="#BFBFBF" disabled>
  - `$adGray1`: #FFF <input type="color" value="#FFFFFF" disabled>
  - `$adGray2`: #FAFAFA <input type="color" value="#FAFAFA" disabled>
  - `$adGray3`: #F5F5F5 <input type="color" value="#F5F5F5" disabled>
  - `$adGray4`: #E8E8E8 <input type="color" value="#E8E8E8" disabled>
  - `$adGray5`: #D9D9D9 <input type="color" value="#D9D9D9" disabled> (border)
  - `$adGray6`: #BFBFBF <input type="color" value="#BFBFBF" disabled>
  - `$adGray7`: #8C8C8C <input type="color" value="#8C8C8C" disabled>
  - `$adGray8`: #595959 <input type="color" value="#595959" disabled>
  - `$adGray9`: #262626 <input type="color" value="#262626" disabled>
  - `$adGray10`: #000 <input type="color" value="#000000" disabled>
  - `$adGrey`: #BFBFBF <input type="color" value="#BFBFBF" disabled>
  - `$adGrey1`: #FFF <input type="color" value="#FFFFFF" disabled>
  - `$adGrey2`: #FAFAFA <input type="color" value="#FAFAFA" disabled>
  - `$adGrey3`: #F5F5F5 <input type="color" value="#F5F5F5" disabled>
  - `$adGrey4`: #E8E8E8 <input type="color" value="#E8E8E8" disabled>
  - `$adGrey5`: #D9D9D9 <input type="color" value="#D9D9D9" disabled> (border)
  - `$adGrey6`: #BFBFBF <input type="color" value="#BFBFBF" disabled>
  - `$adGrey7`: #8C8C8C <input type="color" value="#8C8C8C" disabled>
  - `$adGrey8`: #595959 <input type="color" value="#595959" disabled>
  - `$adGrey9`: #262626 <input type="color" value="#262626" disabled>
  - `$adGrey10`: #000 <input type="color" value="#000000" disabled>
- project preset styles
  - `$headerHeight`: 96rpx
  - `$headerVerticalPadding`: 0
  - `$headerHorizontalPadding`: 24rpx
  - `$footerHeight`: 120rpx
  - `$footerVerticalPadding`: 0
  - `$footerHorizontalPadding`: 24rpx
  - `$borderRadius`: 8rpx
  - `$textTitleColor`: rgba(0, 0, 0, .85)
  - `$textTitleLightColor`: rgba(0, 0, 0, .75)
  - `$textMainColor`: rgba(0, 0, 0, .65)
  - `$textMainLightColor`: rgba(0, 0, 0, .55)
  - `$textSecondaryColor`: rgba(0, 0, 0, .45)
  - `$textDisabledColor`: rgba(0, 0, 0, .25)
  - `$borderColor`: #D9D9D9 <input type="color" value="#D9D9D9" disabled>

## [global.scss](./global.scss)

### example in taro / uni-app

```js
// in entry js/vue/jsx
import '@modyqyw/css-styles/web/global.scss'
```

taro:

```jsx
import Taro, { Component } from '@tarojs/taro'
import { View } from '@tarojs/components'

export default class Index extends Component {
  render() {
    return (
      <View className='item' />
    )
  }
}
```

uni-app:

```js
<template>
  <view class="item" />
</template>
```

### content

```scss
@import "./vars";

/* layout */
html,
body,
#app,
#root {
  box-sizing: border-box;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

page {
  box-sizing: border-box;
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
  overflow: hidden;
  font-size: 28rpx;
  font-weight: 400;
  line-height: 44rpx;
}

.border-box {
  box-sizing: border-box;
}

.container {
  position: relative;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  width: 100%;
  height: 100%;

  .header,
  .footer {
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    background-color: $white;

    .left,
    .right {
      box-sizing: border-box;
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      height: 100%;
      overflow: hidden;
    }

    .left {
      flex: auto;
      justify-content: flex-start;
    }

    .right {
      flex: none;
      justify-content: flex-end;
    }
  }

  .header {
    flex: 0 0 $headerHeight;
    padding: $headerVerticalPadding $headerHorizontalPadding;
    border-bottom: 2rpx solid $borderColor;
  }

  .footer {
    flex: 0 0 $footerHeight;
    padding: $footerVerticalPadding $footerHorizontalPadding;
    border-top: 2rpx solid $borderColor;
  }

  .aside {
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    width: auto;
    height: 100%;
  }

  .main {
    box-sizing: border-box;
    display: flex;
    flex: auto;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    width: 100%;
    height: auto;
  }

  &.is-horizontal {
    flex: 1;
    flex-direction: row;
    height: auto;

    .main {
      width: auto;
      height: 100%;
    }
  }
}

// item
.item {
  position: relative;
  box-sizing: border-box;
  display: flex;
  width: 100%;
  height: 100%;
}

.row-item {
  position: relative;
  box-sizing: border-box;
  display: flex;
  width: 100%;
}

.col-item {
  position: relative;
  box-sizing: border-box;
  display: flex;
  height: 100%;
}

.center-item {
  position: relative;
  box-sizing: border-box;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flex {
  display: flex;
}

.flex-auto {
  flex: auto;
}

.flex-none {
  flex: none;
}

.flex-row {
  flex-direction: row !important;
}

.flex-col {
  flex-direction: column !important;
}

.flex-nowrap {
  flex-wrap: nowrap !important;
}

.flex-wrap {
  flex-wrap: wrap !important;
}

.align-content-center {
  align-content: center !important;
}

.align-content-start {
  align-content: flex-start !important;
}

.align-content-end {
  align-content: flex-end !important;
}

.align-content-space-around {
  align-content: space-around !important;
}

.align-content-space-between {
  align-content: space-between !important;
}

.align-content-stretch {
  align-content: stretch !important;
}

.align-items-center {
  align-items: center !important;
}

.align-items-start {
  align-items: flex-start !important;
}

.align-items-end {
  align-items: flex-end !important;
}

.align-items-stretch {
  align-items: stretch !important;
}

.align-self-auto {
  align-self: auto !important;
}

.align-self-center {
  align-self: center !important;
}

.align-self-start {
  align-self: flex-start !important;
}

.align-self-end {
  align-self: flex-end !important;
}

.align-self-stretch {
  align-self: stretch !important;
}

.justify-content-center {
  justify-content: center !important;
}

.justify-content-start {
  justify-content: flex-start !important;
}

.justify-content-end {
  justify-content: flex-end !important;
}

.justify-content-space-around {
  justify-content: space-around !important;
}

.justify-content-space-between {
  justify-content: space-between !important;
}

.justify-content-space-evenly {
  justify-content: space-evenly !important;
}

// overflow
.overflow-hidden {
  overflow: hidden;
}

.overflow-auto {
  overflow: auto;
}

.overflow-x-hidden {
  overflow: hidden auto;
}

.overflow-y-hidden {
  overflow: auto hidden;
}

.overflow-x-auto {
  overflow: auto hidden;
}

.overflow-y-auto {
  overflow: hidden auto;
}

/* button */
[class^="btn-"] {
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  height: 80rpx;
  padding: 0;
  margin: 0;
  font-size: 28rpx;
  line-height: 44rpx;
  color: $black;
  text-align: center;
  border: none;

  &::after {
    border: none;
  }

  &[disabled] {
    background-color: $borderColor;
  }
}

.btn-border {
  border: 2rpx solid $black;
}

.btn-radius {
  border-radius: 8rpx;
}

/* typography */
page,
#app,
#root {
  font-family:
    -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang SC",
    "Hiragino Sans GB", "Microsoft YaHei", Avenir, "Helvetica Neue",
    Helvetica, Arial, sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol";
  font-variant-numeric: tabular-nums;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.text-thin {
  font-weight: 100;
}

.text-extra-light,
.text-ultra-light {
  font-weight: 200;
}

.text-light {
  font-weight: 300;
}

.text-regular,
.text-normal {
  font-weight: 400;
}

.text-medium {
  font-weight: 500;
}

.text-semi-bold {
  font-weight: 600;
}

.text-bold {
  font-weight: 700;
}

.text-extra-bold,
.text-ultra-bold {
  font-weight: 800;
}

.text-black,
.text-heavy {
  font-weight: 900;
}

.text-12 {
  font-size: 24rpx;
  line-height: 40rpx;
}

.text-13 {
  font-size: 26rpx;
  line-height: 42rpx;
}

.text-14 {
  font-size: 28rpx;
  line-height: 44rpx;
}

.text-15 {
  font-size: 30rpx;
  line-height: 46rpx;
}

.text-16 {
  font-size: 32rpx;
  line-height: 48rpx;
}

.text-17 {
  font-size: 34rpx;
  line-height: 50rpx;
}

.text-18 {
  font-size: 36rpx;
  line-height: 52rpx;
}

.text-19 {
  font-size: 38rpx;
  line-height: 54rpx;
}

.text-20 {
  font-size: 40rpx;
  line-height: 56rpx;
}

.text-21 {
  font-size: 42rpx;
  line-height: 58rpx;
}

.text-22 {
  font-size: 44rpx;
  line-height: 60rpx;
}

.text-23 {
  font-size: 46rpx;
  line-height: 62rpx;
}

.text-24 {
  font-size: 48rpx;
  line-height: 64rpx;
}

.text-truncate {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}

.text-italic {
  font-style: italic;
}

.text-disabled {
  color: $textDisabledColor;
}

.text-title {
  font-size: 36rpx;
  line-height: 52rpx;
  color: $textTitleColor;
}

.text-title-light {
  font-size: 32rpx;
  line-height: 48rpx;
  color: $textTitleLightColor;
}

.text-main {
  font-size: 28rpx;
  line-height: 44rpx;
  color: $textMainColor;
}

.text-main-light {
  font-size: 26rpx;
  line-height: 42rpx;
  color: $textMainLightColor;
}

.text-secondary {
  font-size: 24rpx;
  line-height: 40rpx;
  color: $textSecondaryColor;
}
```
