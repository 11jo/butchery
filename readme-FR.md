# BuTcHeRy

**Auteur :** DrAzTiK

**Version :** 4.0.0

**Langues :** fran�ais, <a href="readme.md">anglais</a>

**Plateforme :** Windows</br></br>



## Pr�sentation

L'objet principal de ce petit mod est d'ajouter un combat dynamique et plus relev� dans le repaire de Firkraag.

J'aime Baldur's Gate, et j'ai �crit ce mod (premi�re version en 2010) pour comprendre un minimum les arcanes du modding. Gr�ce � Freddy_Gwendo, ce mod est d�sormais compatible avec les versions am�lior�es (BG2:EE). Je lui aussi r�cemment apport� certaines am�liorations et des ajustements.

Par ailleurs, ce mod a pour ambition de :

- Permettre aux joueurs de conduire un combat "�pique" dans de large espaces car j'ai toujours eu horreur de combattre dans des corridors (ce qui est malheureusement fr�quent dans BG2).
- Ajuster la difficult� du combat selon la mani�re dont le joueur r�gle le curseur de difficult� accessible dans le menu Options du jeu (voir la section Composants de ce document).
- G�n�rer des combats dynamiques avec des spawns/respawns d'ennemis pour pimenter les choses.
- Am�liorer l�g�rement certaines cr�atures de type "guerrier au corps � corps" en leur ajoutant un kit, des points de comp�tences martiales, etc.
- Am�liorer le charisme de certains boss (Tazok et Dig-Dag).
- Assurer une int�gration et une compatibilit� totales avec stratagems et Item Revisions (especially potions revisions component).
- Conserver le contenu du jeux original.
- Apporter un ou deux �l�ments comiques � l'aventure.
- Ne pas offrir de r�compenses disproportionn�s.



## Compatibilit�

Ce mod est con�u pour fonctionner sur les jeux Infinity Engine suivants : Baldur's Gate II: Enhanced Edition (BG2EE), le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA), avec son extension Tr�ne de Bhaal (Throne of Bhaal : ToB), les mods de conversion Baldur's Gate Trilogy (BGT) et Enhanced Edition Trilogy (EET).

BuTcHeRy est un mod <acronym title="Weimer Dialogue Utility">WeiDU</acronym> et devrait par cons�quent �tre compatible avec n'importe quel mod WeiDU. Si vous faites face � des bugs, veuillez les signaler dans le forum, s'il vous pla�t.

Bien que je m'efforce de rendre BuTcHeRy compatible avec le plus grand nombre possible de mods, des incompatibilit�s risquent toujours de se produire. Voici la liste de celles recens�es jusqu'� pr�sent :

- BuTcHeRY n'est pas compatible avec le composant � Firkraag amelior� � du mod Revisited Battles.
- Comme j'utilise les scripts de combat propos�s par le jeux original, vous pouvez encore augmenter la difficult� si vous installez le mod stratagems (composant � IA g�n�rale plus efficace �) qui am�liorera mes scripts de combat. Bien �videmment, vous devrez installer stratagems apr�s BuTcHeRy.</br></br>

Si vous jouez avec BG2-ToB ou BGT, je vous recommande fortement d'installer la derni�re version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.</br></br>



## Installation

#### Mise en garde

<em>Si une ancienne version de ce mod est d�j� install�e, il est n�cessaire de la d�sinstaller d'abord. Pour cela, lancez <strong>setup-butchery.exe</strong> et d�sinstallez tous les composants pr�c�demment install�s. Une fois la d�sinstallation achev�e, supprimez le r�pertoire <strong>butchery</strong> et le fichier <strong>setup-butchery.exe</strong> avant d'extraire la nouvelle version du mod.</em>

<em>Lorsque vous installez ou d�sinstallez, <strong>ne fermez pas la fen�tre <acronym title="Disk Operating System">DOS</acronym></strong> en cliquant sur le bouton <strong>X</strong> ! Au lieu de cela, appuyez sur la touche <strong>Entr�e</strong> lorsque l'invite de commandes vous le demande.</em>

<em>Par pr�caution, <strong>d�sactivez les antivirus</strong> ou tout logiciel r�sidant en m�moire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une f�cheuse tendance � d�clarer les ex�cutables des mods comme des faux positifs, provoquant ainsi l'�chec de la proc�dure d'installation.</em>


#### Note pour les jeux en �dition Am�lior�e (EE)

Les �ditions am�lior�es sont des jeux que le d�veloppeur fait encore �voluer, notamment par l'ajout de capacit�s suppl�mentaires destin�es � la cr�ation de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise � jour effacera les mods que vous avez install�s ! Ce mod ne fera pas exception � la r�gle.

Si vous pouvez retarder la mise � jour du patch en plein milieu d'un partie modd�e (si vous en avez la possibilit�, notamment chez Beamdog et Good Old Games), n'oubliez pas que m�me apr�s avoir r�install� les mods sur un nouveau patch, vous ne pourrez peut-�tre pas continuer le jeu avec vos anciennes sauvegardes, en particulier � cause de noms de personnages, de lieux, etc. qui pourraient �tre incorrects. Pour y rem�dier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifi� par les patches de mise � jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.


#### Windows

BuTcHeRy pour Windows est livr� et install� avec <acronym title="Weimer Dialogue Utility">WeiDU</acronym>, et est diffus� sous forme d'archive

Vous devez extraire les fichiers de l'archive dans votre r�pertoire de jeu. Une fois l'archive extraite correctement, vous devriez trouver le r�pertoire <strong>butchery</strong> et le fichier <strong>setup-butchery.exe</strong> dans votre r�pertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur <strong>setup-butchery.exe</strong> et de suivre les instructions affich�es � l'�cran.

Vous pouvez lancer <strong>setup-butchery.exe</strong> dans votre r�pertoire de jeu pour r�installer, d�sinstaller, ou encore changer des composants.


#### Note pour effectuer une d�sinstallation compl�te

En plus des m�thodes d�taill�es plus haut pour supprimer des composants, il est possible de d�sinstaller compl�tement le mod en tapant <strong>setup-butchery --uninstall</strong> dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.</br></br>



## Composants

Le programme d'installation comprend les composants suivants. Chacun poss�de un num�ro distinct et pr�-d�fini qui lui attribue une position d�termin�e (mot-cl� <em>DESIGNATED</em> en langage WeiDU) ; ce qui permet aux autres composants de le d�tecter et aux utilitaires d'installation automatiques comme le BiG World Setup de pr�ciser quels composants installer.


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
				<th>Niveau <span style="font-weight: normal">(ex)</span></th>
				<th>XP <span style="font-weight: normal">(ex)</span></th>
				<th>PV <span style="font-weight: normal">(ex)</span></th>
				<th>Force <span style="font-weight: normal">(ex)</span></th>
				<th>Constitution <span style="font-weight: normal">(ex)</span></th>
				<th>Comp�tence martiale</th>
			</tr>
			<tr>
				<td>OGRE01</td>
				<td>Berserker</td>
				<td>5 (4)</td>
				<td>600 (270)</td>
				<td>50 (30)</td>
				<td>21 (18/100)</td>
				<td>18 (9)</td>
				<td>MORNING STAR & MACE +++</td>
			</tr>
			<tr>
				<td>ORC01</td>
				<td>Barbare</td>
				<td>5 (4)</td>
				<td>600 (95)</td>
				<td>60 (35)</td>
				<td>19 (18/10)</td>
				<td>18 (9)</td>
				<td>AXE ++</td>
			</tr>
			<tr>
				<td>ORC02</td>
				<td>--</td>
				<td>5</td>
				<td>600 (35)</td>
				<td>50 (35)</td>
				<td>18 (11)</td>
				<td>17 (10)</td>
				<td>COMPOSITE LONG BOW +++ & BASTARD ++</td>
			</tr>
			<tr>
				<td>ORC05 (Orog)</td>
				<td>Barbare</td>
				<td>7 (5)</td>
				<td>800 (600)</td>
				<td>84 (40)</td>
				<td>20 (18/53)</td>
				<td>20 (9)</td>
				<td>TWO-HANDED SWORD +++</td>
			</tr>
			<tr>
				<td>ORC06 (Orog)</td>
				<td>Berserker</td>
				<td>7 (5)</td>
				<td>800 (175)</td>
				<td>70 (40)</td>
				<td>20 (18/92)</td>
				<td>20 (9)</td>
				<td>TWO-HANDED SWORD +++</td>
			</tr>
			</tr>
		</table><br>


#### 30. R��quilibrage de Tazok et de DigDag

Ce composant am�liore un peu Tazok et DigDag (statistiques, jets de sauvegarde, points de comp�tences...). DigDag est dot� d'un kit de berserk. Je n'ai pas ajout� de kit � Tazok car stratagems le fait d�j� (� IA g�n�rale plus efficace �). Ce composant est aussi cosm�tique : Tazok est de nouveau un demi-ogre (comme dans BG1) tandis que DigDag endosse l'animation de chef orog.

<table style="margin-left: 80px" summary="Rebalanced Tazok and Dig-Dag">
			<tr>
				<th>Cr�ature</th>
				<th>Kit</th>
				<th>Niveau <span style="font-weight: normal">(ex)</span></th>
				<th>XP <span style="font-weight: normal">(ex)</span></th>
				<th>PV <span style="font-weight: normal">(ex)</span></th>
				<th>Force <span style="font-weight: normal">(ex)</span></th>
				<th>Constitution <span style="font-weight: normal">(ex)</span></th>
				<th>Comp�tence martiale</th>
			</tr>
			<tr>
				<td>Tazok</td>
				<td>--</td>
				<td>19 (18)</td>
				<td>12000 (6000)</td>
				<td>154 (136)</td>
				<td>--</td>
				<td>--</td>
				<td>TWO-HANDED SWORD +++++</td>
			</tr>
			<tr>
				<td>FIRorc01 (DigDag)</td>
				<td>Berserker</td>
				<td>13 (12)</td>
				<td>7000 (2000)</td>
				<td>107 (99)</td>
				<td>22 (17)</td>
				<td>22 (9)</td>
				<td>BASTARD SWORD +++++</td>
		</table><br>



## Captures d'�cran

<img src="butchery/images/baldr000.jpg">
<img src="butchery/images/baldr001.jpg"></br>



## Cr�dits et remerciements

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
###### S'il existe des probl�mes de droits d'auteur ou si cette d�claration n�cessite une r�vision, veuillez me contacter et conseillez-moi sur ce qu'il faut faire � ce sujet. Plus particuli�rement, si vous trouvez dans ce mod des illustrations susceptibles d��tre en conflit avec les r�gles de droit d�auteur, merci de bien vouloir me le faire savoir d�s que possible et je supprimerai imm�diatement le contenu en conflit.
###### Ce mod a �t� cr�� pour �tre librement appr�ci� par tous les joueurs de Baldur's Gate II et son contenu est libre de droit. N"h�sitez pas � lui � emprunter � ce qui vous int�resse, je promets de ne pas vous en vouloir.</br></br>



## Version History

#### Version 4.0.0 - 1x octobre 2018

- General overhaul and relooking:

	- Integrated all BWP Fixpack patches: <a href="http://www.shsforums.net/topic/42220-fixes-for-the-big-fixpack/?p=524893">Lollorian's override compilation fix</a> (changes COMPILE xyz.d/baf override to COMPILE xyz.d/baf) and unknown origin patch that set ORC05.CRE's BG1 Long Swords proficiency to 0.
	- Provides full compatibility with stratagems and Item revisions.
	- tp2 split into components and commented for easier further updates.
	- Reorganized components (DESIGNATED numbers).
	- Added BG2EE compatibility (probably with EET, but not yet tested).
	- Fixed wrong coding: turned WRITE_SHORT 0x028 to WRITE_LONG 0x028 (animation slot is a dword, not a word!) and WRITE_BYTE 0x242 to WRITE_SHORT 0x242 (Morale recovery is a word, not a byte).
	- Polished WRITE_ASCII command with #n.
	- No longer overwrites mod item files if there are already installed.
	- Uses new WeiDU variables (INV RING QITEM...) with ADD_CRE_ITEM command.
	- Provides new portraits for BG2:EE.
	- Reworked install procedure to use WeiDU's built-in HANDLE_AUDIO function to install soundsets.
	- Uses HANDLE_CHARSETS function to add BG2EE compatibility for languages other than English.
	- Deleted unused files from mod folder.
	- Updated readme (Butchery now supports translated readmes)
	- Revamped French translation courtesy of Gwendolyne.
	- Traified creatures soundsets (still waiting for English sound files).
	- Reorganized and merged tra files into 3 files.
	- Updated <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer to v246.

- Components specific modifications and fixes: please read the <a href="https://raw.githubusercontent.com/GwendolyneFreddy/butchery/master/butchery/change-log.txt">change-log file</a>.


#### Version 3.2 - 10 Octobre 2011
- Increased Tazok to level 19 Barbarian.
- Added a magical armor to Tazok.
- Increased DigDag to level 13 Berseker.
- Decreased the number of Orcs spawned in final fight.


#### Version 3 - 1er Mars, 2011
- Better compatibility with SCS II (especially more sensible choices of weapon proficiencies and kits for fighters component).


#### Version 2 - 30 novembre 2010
- Added French translation.


#### Version 1 - 11 novembre 2010
- Initial release.