
![Latest Release](https://img.shields.io/github/v/release/GwendolyneFreddy/butchery?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/GwendolyneFreddy/butchery?color=gold)
![Platform](https://img.shields.io/static/v1?label=plateformes&message=windows%20%7C%20macOS%20%7C%20linux%20%7C%20Project%20Infinity&color=informational)
![Language](https://img.shields.io/static/v1?label=langues&message=Fran%C3%A7ais%20%7C%20Anglais%20%7C%20Russe&color=limegreen)

![Supported games](https://img.shields.io/static/v1?label=supported%20games&message=BGII:ToB%20%7C%20BGT%20%7C%20BG2%3AEE%20%7C%20EET&color=dodgerblue)
<a href="README_EN.md"><img align="right" src="butchery/readme/images/uk-flag-32.png" title="English Readme"></a>


<div align="center"><h1><BuTcHeRy</h1>

<h3>Un mod d�velopp� sur <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> pour Baldur's Gate II: ToB,<br>
BGT, BG2:EE et EET<h3>
</div><br>

**Auteur :** <a href="https://www.baldursgateworld.fr/lacouronne/members/draztik.html">DrAzTiK</a>  
**Site du mod :** <a href="https://www.baldursgateworld.fr/lacouronne/modules-crees-ou-en-cours-de-developpement/">La Couronne de Cuivre</a>  
**Forum du mod :** <a href="https://www.baldursgateworld.fr/lacouronne/butchery/">BuTcHeRy</a>

## 

[![Created Badge](https://badges.pufler.dev/created/GwendolyneFreddy/butchery?style=plastic&label=cr%C3%A9ation)](https://badges.pufler.dev)
![GitHub repo size](https://img.shields.io/github/repo-size/GwendolyneFreddy/butchery?style=plastic&label=taille)
[![Visits Badge](https://badges.pufler.dev/visits/GwendolyneFreddy/butchery?color=cyan&style=plastic&label=visites)](https://badges.pufler.dev) 
![Maintenance](https://img.shields.io/static/v1?label=maintenu%20%3F&message=oui&color=greenlight&style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/GwendolyneFreddy/butchery?color=blueviolet&label=contributeurs&style=plastic) [![Contributors Display](https://badges.pufler.dev/contributors/GwendolyneFreddy/butchery?size=30&padding=5&bots=true)](https://badges.pufler.dev)

## 

:page_facing_up: [Lisez-moi du mod]()

:inbox_tray: [T�l�charger le mod sur le site de La Couronne de Cuivre]()<br>

## 

<div align="center">
<a href="#intro">Pr�sentation</a> &#8226; <a href="#compat">Compatibilit�</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#components">Composants</a> &#8226; <a href="#componentslist">Composants (pr�sentation alternative</a> &#8226; <a href="#images">Captures d'�cran</a> &#8226; <a href="#credits">Cr�dits et remerciements</a> &#8226; <a href="#versions">Historique des versions</a><br>
</div>


<hr>


## <a name="intro" id="intro"></a>Pr�sentation

L'objet principal de ce petit mod est d'ajouter un combat dynamique et plus relev� dans le repaire de Firkraag.

J'aime Baldur's Gate, et j'ai �crit ce mod (premi�re version en 2010) pour comprendre un minimum les arcanes du modding. Gr�ce � Freddy_Gwendo, ce mod est d�sormais compatible avec les versions am�lior�es (BG2:EE). Je lui ai aussi r�cemment apport� certaines am�liorations et des ajustements.

Par ailleurs, ce mod a pour ambition de :

- Permettre aux joueurs de conduire un combat � �pique � dans de large espaces car j'ai toujours eu horreur de combattre dans des corridors (ce qui est malheureusement fr�quent dans BG2).
- Ajuster la difficult� du combat selon la mani�re dont le joueur r�gle le curseur de difficult� accessible dans le menu Options du jeu (voir la section <a href="#components">Composants</a> de ce document).
- G�n�rer des combats dynamiques avec des spawns/respawns d'ennemis pour pimenter les choses.
- Am�liorer l�g�rement certaines cr�atures de type � guerrier au corps � corps � en leur ajoutant un kit, des points de comp�tences martiales, etc.
- Am�liorer le charisme de certains boss (Tazok et DigDag).
- Assurer une int�gration et une compatibilit� totales avec stratagems et Item Revisions (en particulier son composant � *R�vision des potions* �).
- Conserver le contenu du jeux original.
- Apporter un ou deux �l�ments comiques � l'aventure.
- Ne pas offrir de r�compenses disproportionn�s.
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibilit�

#### Jeux concern�s

Ce mod est con�u pour fonctionner sur les jeux Infinity Engine suivants :
- Baldur's Gate II: Enhanced Edition (BG2EE).
- Le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA), avec son extension Tr�ne de Bhaal (Throne of Bhaal : ToB). *Assurez-vous que l'extension Tr�ne de Bhaal dispose bien du patch 26498. V�rifiez le num�ro de cette version dans le fichier readme de votre r�pertoire de jeu, et consultez �ventuellement <a href="http://www.bioware.com/games/throne_bhaal/support/patches/">le site de BioWare</a>.*
- Les mods de conversion bas�s sur le moteur ToB : <a href="http://www.shsforums.net/forum/261-bgt-weidu/">Baldur's Gate Trilogy</a> (BGT)et <a href="https://github.com/Gibberlings3/EET/releases">Enhanced Edition Trilogy</a> (EET).

## 

#### Compatibilit� avec les autres mods

Ce mod est un mod WeiDU et devrait par cons�quent �tre compatible avec n'importe quel mod WeiDU. Bien que je m'efforce de rendre BuTcHeRy compatible avec le plus grand nombre possible de mods, des incompatibilit�s risquent toujours de se produire. Voici la liste de celles recens�es jusqu'� pr�sent :

- BuTcHeRY n'est pas compatible avec le composant � *Firkraag amelior�<* � du mod Revisited Battles.
- Comme j'utilise les scripts de combat propos�s par le jeux original, vous pouvez encore augmenter la difficult� si vous installez le mod stratagems (composant � *IA g�n�rale plus efficace* �) qui am�liorera mes scripts de combat. Bien �videmment, vous devrez installer stratagems apr�s BuTcHeRy.<br><br>

Si vous rencontrez des bugs, veuillez les signaler dans le <a href="https://www.baldursgateworld.fr/lacouronne/butchery/">le forum du mod</a>, s'il vous pla�t.

## 

#### Ordre d'installation

>Je recommande fortement aux joueurs de ToB original de t�l�charger et d'installer la derni�re version du <a href="https://www.gibberlings3.net/mods/fixes/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.<br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Mise en garde

*Si une ancienne version de ce mod est d�j� install�e, il est n�cessaire de la d�sinstaller avant d'extraire la nouvelle. Pour cela, lancez __`setup-butchery.exe`__, et d�sinstallez tous les composants pr�c�demment install�s. Une fois la d�sinstallation achev�e, supprimez le r�pertoire :file_folder: __butchery__ et le fichier __setup-butchery.exe__ (version Windows) avant d'extraire la nouvelle version du mod.*

*Lorsque vous installez ou d�sinstallez, __ne fermez pas la fen�tre DOS__ en cliquant sur le bouton __X__ ! Au lieu de cela, appuyez sur la touche __Entr�e__ lorsque l'invite de commandes vous le demande.*

*Par pr�caution, __d�sactivez les antivirus__ ou tout logiciel r�sidant en m�moire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une f�cheuse tendance � d�clarer les ex�cutables des mods comme des faux positifs, provoquant ainsi l'�chec de la proc�dure d'installation.*

Vous pouvez extraire les fichiers de l'archive � l'aide de <a href="https://www.7-zip.org/download.html">7zip</a>, <a href="https://www.rarlab.com/download.htm">WinRAR</a>, <a href="https://zipgenius.com/">ZipGenius</a>, ou de tout autre utilitaire de compression g�rant les fichiers .zip.
## 

#### Note pour les jeux en �dition Am�lior�e (EE)

Les �ditions am�lior�es sont des jeux que le d�veloppeur fait encore �voluer, notamment par l'ajout de capacit�s suppl�mentaires destin�es � la cr�ation de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise � jour effacera les mods que vous avez install�s ! Ce mod ne fera pas exception � la r�gle.

Si vous pouvez retarder la mise � jour du patch en plein milieu d'un partie modd�e (si vous en avez la possibilit�, notamment chez Beamdog et Good Old Games), n'oubliez pas que m�me apr�s avoir r�install� les mods sur un nouveau patch, vous ne pourrez peut-�tre pas continuer le jeu avec vos anciennes sauvegardes, en particulier � cause de noms de personnages, de lieux, etc, qui pourraient �tre incorrects. Pour y rem�dier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifi� par les patches de mise � jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.

## 

#### Windows

BuTcHeRy pour Windows est livr� et install� avec WeiDU, et est diffus� sous forme d'archive

Vous devez extraire les fichiers de l'archive dans votre r�pertoire de jeu (*le dossier qui contient le fichier CHITIN.KEY*). Une fois l'archive extraite correctement, vous devriez trouver le r�pertoire :file_folder: butchery et le fichier setup-butchery.exe dans votre r�pertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur **`setup-butchery.exe<`** et de suivre les instructions affich�es � l'�cran.

Pour r�installer, d�sinstaller ou changer certains composants, lancez **`setup-butchery.exe`** dans votre r�pertoire de jeu.

## 

#### Mac OS

BuTcHeRy pour Mac OS est livr� avec WeiDU et est diffus� dans la m�me archive compress�e.

Extrayez le contenu de l'archive dans votre r�pertoire de jeu. Apr�s une extraction r�ussie, ce dernier contiendra les fichiers setup-butchery, setup-butchery.command et le r�pertoire :file_folder: butchery. Pour installer, il suffit de double-cliquer sur **`setup-butchery.command`** et de suivre les instructions affich�es � l'�cran.

Vous pouvez lancer **`setup-butchery.command`** dans votre r�pertoire de jeu pour r�installer, d�sinstaller ou changer des composants.

## 

#### Linux

BuTcHeRy pour Linux est diffus� dans la m�me archive compress�e, mais sans l'installateur WeiDU.

Extrayez le contenu du mod dans le r�pertoire du jeu que vous voulez modifier.

T�l�chargez la version la plus r�cente de WeiDU pour Linux sur <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a>, puis copiez weidu et weinstall dans `/usr/local/bin` (cr�ez-le s'il n'existe pas). Ouvrez ensuite un terminal et allez (**`cd`**) dans le r�pertoire d'installation de votre jeu, lancez **`/usr/local/bin/tolower`** et r�pondez � Y � aux deux questions. Vous pouvez �viter d'ex�cuter la seconde option (linux.ini) si vous l'avez d�j� lanc�e une fois dans le m�me dossier. Pour gagner du temps, l'archive est d�j� pass�e en minuscules, aussi il n'est pas non plus n�cessaire d'ex�cuter la premi�re option (passer les noms de fichiers en minuscules) si vous n'avez extrait que ce mod depuis la derni�re fois que vous avez pass� les noms de fichiers en minuscules. Si vous avez un doute, il vaut mieux ex�cuter tolower et accepter les deux options.

Tapez la commande **`export PATH=$PATH:/usr/local/bin`**, puis lancez **`weinstall setup-butchery`** depuis le dossier de votre jeu pour installer le mod. Ex�cutez ensuite **`wine bgmain.exe`** (ou **`wine baldur.exe`** pour les jeux EE) et commencez votre partie.

## 

#### Note pour effectuer une d�sinstallation compl�te

En plus des m�thodes d�taill�es plus haut pour supprimer des composants, il est possible de d�sinstaller compl�tement le mod en tapant **`setup-butchery --uninstall`** dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.<br><br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="components" id="components"></a>Composants

Le programme d'installation comprend les composants suivants. Chacun poss�de un num�ro distinct et pr�-d�fini qui lui attribue une position d�termin�e (mot-cl� <em>DESIGNATED</em> en langage WeiDU) ; ce qui permet aux autres composants et aux autres mods de le d�tecter et aux utilitaires d'installation automatiques comme le BiG World Setup de pr�ciser quels composants installer.


#### 10. Combat contre Tazok et DigDag r�vis� par DrAzTiK

J'ai toujours trouv� tr�s path�tique le combat contre Tazok et DigDag. � mon avis, le dragon rouge Firkraag est sens� �tre un boss optionnel (comme le dragon de l'ombre), en th�orie imbattable avant la sortie des Tr�fonds obscurs.

J'ai donc pens� � am�liorer le combat final en faisant de Tazok et DigDag des boss plus puissants et charismatiques, et surtout en les affrontant dans un endroit plus spacieux. Ne vous inqui�tez pas, vous pourrez aussi affronter Firkraag comme dans le jeu original.

Ce composant ajoute aussi deux guerriers de ma composition avec des soundsets un peu comiques (dont un emprunt� � Pen of Chaos).

##### Modification de la difficult� :

Il s'agit de l'am�lioration la plus r�cente de ce mod. Je sais qu'il peut �tre frustrant d'avoir un combat bien trop difficile, ou � l'inverse bien trop facile, et je voulais y apporter une solution. Le nombre et la vari�t� des opposants seront ajust�s en fonction du r�glage du curseur de difficult� dans le menu Options du jeu. Les ajustements sont les suivants :

- R�gles de base : nombre normal et d�cent d'ennemis (pas de pr�tres ou de mages).
- Difficile : plus d'ennemis et apparitions de quelques pr�tres et de mages.
- Tr�s difficile : encore un peu plus d'ennemis et un peu plus de pr�tres ou de mages.

Je vous pr�viens que le challenge sera s�rement d�j� correct en mode � r�gles de base � car je pars du principe que ce mod s'adresse � des personnes aimant le challenge et ma�trisant un minimum le syst�me de combat.


#### 20. R��quilibrage de certaines cr�atures g�n�riques (orques et ogres)

Ce composant am�liore un peu les statistiques, jets de sauvegarde et points de comp�tences de quelques cr�atures (orques et ogres notamment). La plupart disposent dor�navant d'un kit de barbare ou de berserker, mais vous devrez installer stratagems pour que ces cr�atures utilisent leurs capacit�s sp�ciales.


<table style="margin-left: 80px" summary="Rebalanced generic creatures">
	<tr>
		<th>Cr�ature</th>
		<th>Kit</th>
		<th>Niveau <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>XP <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>PV <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Force <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Constitution <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Comp�tence martiale</th>
	</tr>
	<tr>
		<td>OGRE01</td>
		<td>Berserker</td>
		<td><strong>5</strong>&#160;&#160;&#160;(4)</td>
		<td><strong>600</strong>&#160;&#160;&#160;(270)</td>
		<td><strong>50</strong>&#160;&#160;&#160;(30)</td>
		<td><strong>20</strong>&#160;&#160;&#160;(18/100)</td>
		<td><strong>18</strong>&#160;&#160;&#160;(9)</td>
		<td>MORNING STAR & MACE +++</td>
	</tr>
	<tr>
		<td>ORC01</td>
		<td>Barbare</td>
		<td><strong>5</strong>&#160;&#160;&#160;(4)</td>
		<td><strong>600</strong>&#160;&#160;&#160;(95)</td>
		<td><strong>50</strong>&#160;&#160;&#160;(35)</td>
		<td><strong>19</strong>&#160;&#160;&#160;(18/10)</td>
		<td><strong>18</strong>&#160;&#160;&#160;(9)</td>
		<td>AXE ++</td>
	</tr>
	<tr>
		<td>ORC02</td>
		<td>--</td>
		<td><strong>5</strong></td>
		<td><strong>600</strong>&#160;&#160;&#160;(35)</td>
		<td><strong>50</strong>&#160;&#160;&#160;(35)</td>
		<td><strong>18</strong>&#160;&#160;&#160;(11)</td>
		<td><strong>17</strong>&#160;&#160;&#160;(10)</td>
		<td>COMPOSITE LONG BOW +++ & BASTARD ++</td>
	</tr>
	<tr>
		<td>ORC05 (Orog)</td>
		<td>Barbare</td>
		<td><strong>7</strong>&#160;&#160;&#160;(4)</td>
		<td><strong>800</strong>&#160;&#160;&#160;(600)</td>
		<td><strong>91</strong>&#160;&#160;&#160;(40)</td>
		<td><strong>20</strong>&#160;&#160;&#160;(18/53)</td>
		<td><strong>20</strong>&#160;&#160;&#160;(9)</td>
		<td>TWO-HANDED SWORD +++</td>
	</tr>
	<tr>
		<td>ORC06 (Orog)</td>
		<td>Berserker</td>
		<td><strong>7</strong>&#160;&#160;&#160;(4)</td>
		<td><strong>800</strong>&#160;&#160;&#160;(175)</td>
		<td><strong>75</strong>&#160;&#160;&#160;40)</td>
		<td><strong>20</strong>&#160;&#160;&#160;(18/92)</td>
		<td><strong>20</strong>&#160;&#160;&#160;(9)</td>
		<td>TWO-HANDED SWORD +++</td>
	</tr>
		</table><br>


#### 30. R��quilibrage de Tazok et de DigDag

Ce composant am�liore un peu Tazok et DigDag (statistiques, jets de sauvegarde, points de comp�tences...). DigDag est dot� d'un kit de berserk. Je n'ai pas ajout� de kit � Tazok car stratagems le fait d�j� (� <em>IA g�n�rale plus efficace</em> �). Ce composant est aussi cosm�tique : Tazok est de nouveau un demi-ogre (comme dans BG1) tandis que DigDag endosse l'animation de chef orog.

<table style="margin-left: 80px" summary="Rebalanced Tazok and Dig-Dag">
	<tr>
		<th>Cr�ature</th>
		<th>Kit</th>
		<th>Niveau <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>XP <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>PV <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Force <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Constitution <span style="font-weight: normal">&#160;&#160;&#160;(ex)</span></th>
		<th>Comp�tence martiale</th>
	</tr>
	<tr>
		<td>Tazok</td>
		<td>--</td>
		<td><strong>19</strong>&#160;&#160;&#160;(18)</td>
		<td><strong>12000</strong>&#160;&#160;&#160;(6000)</td>
		<td><strong>154</strong>&#160;&#160;&#160;(136)</td>
		<td>--</td>
		<td>--</td>
		<td>TWO-HANDED SWORD +++++</td>
	</tr>
	<tr>
		<td>FIRorc01 (DigDag)</td>
		<td>Berserker</td>
		<td><strong>13</strong>&#160;&#160;&#160;(12)</td>
		<td><strong>7000</strong>&#160;&#160;&#160;2000)</td>
		<td><strong>107</strong>&#160;&#160;&#160;(99)</td>
		<td><strong>22</strong>&#160;&#160;&#160;(17)</td>
		<td><strong>22</strong>&#160;&#160;&#160;(9)</td>
		<td>BASTARD SWORD +++++</td>
	</tr>
</table><br>

@20 = ~Rencontre avec Groumf et Bourrinos devant le donjon de Firkraag (a installer avant Stratagems)~

Ce composant ajoute un petit combat et une rencontre amusante avec 2 personnages rigolos devant l'entr�e du donjon de Firkraag, ceux l� m�me qui sont les gardes du corps de Tazok si vous avez install� les composants pr�c�dant.


@21 = ~Rencontre avec Groumf et Bourrinos a Brynnlaw (a installer avant Stratagems)~
Ce composant ajoute un autre petit combat et rencontre amusante avec 2 personnages rigolos.

@22 = ~Rencontre avec Groumf et Bourrinos dans les Tr�fonds Obscurs (a installer avant Stratagems)~
Ce composant ajoute un autre petit combat et rencontre amusante avec 2 personnages rigolos.

<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="images" id="images"></a>Captures d'�cran

<img src="butchery/readme/images/baldr000.jpg">
<img src="butchery/readme/images/baldr001.jpg"><br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="credits" id="credits"></a>Cr�dits et remerciements

#### Auteur : <a href="https://www.baldursgateworld.fr/lacouronne/members/draztik.html">DrAzTiK</a>


#### Remerciements particuliers � :

- L'�quipe de <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a> pour l'h�bergement de ce mod.
- Les cr�ateurs de la s�rie Baldur's Gate : <a href="http://www.bioware.com/">Bioware</a> et <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- Un grand merci � Freddy_Gwendo pour avoir rendu possible la mise � jour de ce mod.
- Merci � Pen of Chaos pour son pack de sons de barbare.
- Merci aux artistes de portraits du site <a href="https://www.pinterest.fr/">Pinterest</a>.
- Merci � toutes les personnes des forums de <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a>, <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a>, et des autres communaut�s de joueurs et de moddeurs IE qui m'ont offert leur aide.


#### Logiciels et outils utilis�s pour la r�alisation de ce mod :

- <a href="http://www.weidu.org/%7Ethebigg/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> de Wes Weimer, the bigg et Wisp.
- <a href="http://forums.pocketplane.net/index.php/topic,25153.msg314249.html#msg314249">Near Infinity</a> de Jon Olav Hauglid, FredSRichardson et Argent77.
- <a href="http://www.shsforums.net/topic/31285-infinity-explorer-v085/">Infinity Explorer</a> de Dmitry Jemerov / bigmoshi.
- <a href="http://www.gibberlings3.net/tools/dltcep.php"><acronym title="Dragonlance Total Conversion Editor Pro">DLTCEP</acronym></a> de Avenger.
- <a href="http://www.baldursgatemods.com/forums/index.php?action=downloads;sa=view;down=85">CreMaker_v3.1.9</a>.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a> maintenu par igi et lynx.
- <a href="http://notepad-plus-plus.org/">Notepad++</a> par l'�quipe de Notepad++, Don Ho, et le plug-in de correction orthographique.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a> de Argent77.
- <a href="http://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a> de TGRMN Software.


#### Information sur les droits d'auteur

###### The BuTcHeRy n'est pas d�velopp�, support� ni approuv� par BioWare&trade; ou Interplay/Black Isle, Overhaul, Beamdog ou Wizards of the Coast. Il a �t� d�velopp� par DrAzTiK, et est bas� sur le jeu Baldur's Gate II et son extension.
###### Baldur's Gate II : Les Ombres d'Amn et Baldur's Gate II : Tr�ne de Bhaal appartiennent � &copy; TSR, Inc. Le moteur Infinity Engine appartient � &copy; BioWare Corp. Toutes les autres marques et droits d'auteur appartiennent � leurs propri�taires respectifs.
###### S'il existe des probl�mes de droits d'auteur ou si cette d�claration n�cessite une r�vision, veuillez me contacter et conseillez-moi sur ce qu'il faut faire � ce sujet. Plus particuli�rement, si vous trouvez dans ce mod des illustrations susceptibles d'�tre en conflit avec les r�gles de droit d'auteur, merci de bien vouloir me le faire savoir d�s que possible et je supprimerai imm�diatement le contenu en conflit.
###### Ce mod a �t� cr�� pour �tre librement appr�ci� par tous les joueurs de Baldur's Gate II et son contenu est libre de droit. N'h�sitez pas � lui � emprunter � ce qui vous int�resse, je promets de ne pas vous en vouloir.<br><br>
<div align="right"><a href="#top">Retour en haut de page</a></div>


<hr>


## <a name="versions" id="versions"></a>Historique des versions

<p>Note du traducteur : l'historique n'est volontairement pas traduit afin de faciliter la mise � jour par l'auteur.</p>

##### Version 5.0.0 &nbsp;(nn septembre 2021)

- .
- Added Russian translation (by yota13).
- .
- .

## 

##### Version 4.0.0 &nbsp;(20 octobre 2018)

- General overhaul and relooking:

	- Integrated all BWP Fixpack patches: <a href="http://www.shsforums.net/topic/42220-fixes-for-the-big-fixpack/?p=524893">Lollorian's override compilation fix</a> (changes `COMPILE xyz.d/baf override` to `COMPILE xyz.d/baf`) and unknown origin patch that set ORC05.CRE's BG1 Long Swords proficiency to 0.
	- Provided full compatibility with stratagems and Item revisions.
	- tp2 split into components and commented for easier further updates.
	- Reorganized components (`DESIGNATED` numbers).
	- Added BG2EE compatibility (probably with EET, but not yet tested).
	- Fixed wrong coding: turned `WRITE_SHORT 0x028` to `WRITE_LONG 0x028` (animation slot is a dword, not a word!) and `WRITE_BYTE 0x242` to `WRITE_SHORT 0x242` (Morale recovery is a word, not a byte).
	- Polished `WRITE_ASCII` command with #n.
	- No longer overwrites mod item files if there are already installed.
	- Used new WeiDU variables (INV RING QITEM...) with `ADD_CRE_ITEM` command.
	- Provided new portraits for BG2:EE.
	- Reworked install procedure to use WeiDU's built-in `HANDLE_AUDIO` function to install soundsets.
	- Used `HANDLE_CHARSETS` function to add BG2EE compatibility for languages other than English.
	- Deleted unused files from mod folder.
	- Updated readme (Butchery now supports translated readmes)
	- Revamped French translation and fixed English typos courtesy of Gwendolyne.
	- Traified creatures soundsets (still waiting for English sound files).
	- Reorganized and merged tra files into 3 files.
	- Updated <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer to v246.

- Components specific modifications and fixes: please read the <a href="https://raw.githubusercontent.com/GwendolyneFreddy/butchery/master/butchery/change-log.txt">change-log file</a>.

## 

##### Version 3.2 &nbsp;(10 octobre 2011)

- Increased Tazok to level 19 Barbarian.
- Added a magical armor to Tazok.
- Increased DigDag to level 13 Berseker.
- Decreased the number of Orcs spawned in final fight.

## 

##### Version 3 &nbsp;(1er mars 2011)

- Better compatibility with SCS II (especially more sensible choices of weapon proficiencies and kits for fighters component).

## 

##### Version 2 &nbsp;(30 novembre 2010)

- Added French translation.

## 

##### Version 1 &nbsp;((11 novembre 2010)

- Initial release.
<div align="right"><a href="#top">Retour en haut de page</a></div>
