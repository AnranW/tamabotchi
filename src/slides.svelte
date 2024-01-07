<script lang="ts">
	import { Presentation, Slide, Media, Step, Stack } from '@components'
	import Layout from './layout.svelte';
</script>

<Presentation>
	<Slide animate id="main">
		<Layout>
			<table class="inline">
				<tr style="border-style:hidden;">
					<td colspan="4">  </td>
					<td class="rounded bg-orange-300" style="font-size:5vh;text-align: center;"> hp 21 </td>
				<tr style="border-style:hidden;">
					<td colspan="1">  </td>
					<td colspan="3"> <img class="h-[40vh]" src="https://www.svgrepo.com/show/2301/robot.svg" alt="central image of robot"> </td>
				</tr>
				<tr style="border-style:hidden;">
					<td colspan="4" style="text-align:center; font-size:5vh;">  
						Friendship with: <span class="rounded bg-red-300">Anran </span>
					</td>
					<td class="rounded bg-red-300" style="font-size:5vh;text-align: center;"> lvl. 7 </td>
				</tr>
			</table>
		</Layout>
	</Slide>
	

	<Slide animate id="charge">
		<Layout>
			<a href="#main">
				<img class="h-full inline" src="https://i.pinimg.com/originals/db/49/58/db4958c8fab9519e8e8e3562b35c6757.gif" alt="charging">
			</a>
		</Layout>
	</Slide>

	<Slide animate id="play">
		<Layout> 
			<a href="#main">
				<img class="h-[full] inline" src="https://media1.giphy.com/media/jUJtNKKVTdIeD0XreN/giphy.gif?cid=6c09b952vj867wh6lh9pkhay7tgurq6tmi07zyhraij65eoi&ep=v1_stickers_related&rid=giphy.gif&ct=s" alt="playing">
			</a>
		</Layout>
	</Slide>

	<Slide animate id="diagnose">
		<Layout> 
			<br>
			<img class="h-[40vh] float-left" src="https://www.svgrepo.com/show/503282/diagnostic-alt.svg" alt="diagnosing">
			<Stack>
				<Step fadeOut> 
					<br>
					<img class="h-[20vh]" src="https://i.gifer.com/CVyf.gif" alt="diagnosing">			
				</Step>			
				<Step fadeIn>
					<br>
					<span style="font-size:5vh"> Follow these instructions:  </span>
				</Step>
			</Stack>
	</Layout>
	</Slide>

	<Slide animate id="diagnose-2">
		<Layout> 
			<Media
				class="h-full w-full inline"
				src="https://www.youtube.com/embed/l8o3O9gLwNU"
				type="iframe"
			  />
		</Layout>
	</Slide>

	<Slide animate id="ecem">
		<Layout>
			<table class="inline">
				<tr style="border-style:hidden;">
					<td colspan="4">  </td>
					<td class="rounded bg-orange-300" style="font-size:5vh;text-align: center;"> hp 21 </td>
				<tr style="border-style:hidden;">
					<td colspan="1">  </td>
					<td colspan="3"> <img class="h-[40vh]" src="https://www.svgrepo.com/show/2301/robot.svg" alt="central image of robot"> </td>
				</tr>
				<tr style="border-style:hidden;">
					<td colspan="4" style="text-align:center; font-size:5vh;">  
						Friendship with: <span class="rounded bg-blue-300">Ecem </span>
					</td>
					<td class="rounded bg-blue-300" style="font-size:5vh;text-align: center;"> lvl. 8 </td>
				</tr>
			</table>
		</Layout>
	</Slide>
	<Slide animate id="ales">
		<Layout>
			<table class="inline">
				<tr style="border-style:hidden;">
					<td colspan="4">  </td>
					<td class="rounded bg-orange-300" style="font-size:5vh;text-align: center;"> hp 21 </td>
				<tr style="border-style:hidden;">
					<td colspan="1">  </td>
					<td colspan="3"> <img class="h-[40vh]" src="https://www.svgrepo.com/show/2301/robot.svg" alt="central image of robot"> </td>
				</tr>
				<tr style="border-style:hidden;">
					<td colspan="4" style="text-align:center; font-size:5vh;">  
						Friendship with: <span class="rounded bg-purple-300">Alessia </span>
					</td>
					<td class="rounded bg-purple-300" style="font-size:5vh;text-align: center;"> lvl. 6 </td>
				</tr>
			</table>
		</Layout>
	</Slide>
	<Slide animate id="animotion">
		<Layout>
			<table class="inline">
				<tr style="border-style:hidden;">
					<td colspan="4">  </td>
					<td class="rounded bg-orange-300" style="font-size:5vh;text-align: center;"> hp 21 </td>
				<tr style="border-style:hidden;">
					<td colspan="1">  </td>
					<td colspan="3"> <img class="h-[40vh]" src="https://www.svgrepo.com/show/2301/robot.svg" alt="central image of robot"> </td>
				</tr>
				<tr style="border-style:hidden;">
					<td colspan="4" style="text-align:center; font-size:5vh;">  
						Friendship with: <span class="rounded bg-yellow-300" style="font-size:4vh;">Animotion </span>
					</td>
					<td class="rounded bg-yellow-300" style="font-size:5vh;text-align: center;"> lvl. 4 </td>
				</tr>
			</table>
		</Layout>
	</Slide>
</Presentation>