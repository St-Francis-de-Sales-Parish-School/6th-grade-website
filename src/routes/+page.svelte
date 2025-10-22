<script>
	const students = [
		{ name: "Sophia Hollenbaugh", url: "https://sophiahollenbaugh.idealab.tools" },
		{ name: "Reagan Dooley", url: "https://reagandooley.idealab.tools" },
		{ name: "Nathan Johnson", url: "https://nathanjohnson.idealab.tools" },
		{ name: "Morgan Miller", url: "https://morganmiller.idealab.tools" },
		{ name: "Katherine Goshe", url: "https://katherinegoshe.idealab.tools" },
		{ name: "Jackson Petit", url: "https://jacksonpetit.idealab.tools" },
		{ name: "Hazel Lightel", url: "https://hazellightel.idealab.tools" },
		{ name: "Evelyn Johnston", url: "https://evelynjohnston.idealab.tools" },
		{ name: "Dylan Cooley", url: "https://dylancooley.idealab.tools" },
		{ name: "Crosby Stanfield", url: "https://crosbystanfield.idealab.tools" },
		{ name: "Conall Crawford", url: "https://conallcrawford.idealab.tools" },
		{ name: "Bryison Macchiarole", url: "https://briysonnmacchiarole.idealab.tools" },
        { name: "Clara Perona", url: "https://claraperona.idealab.tools" },
        { name: "John Quinn", url: "https://johnquinn.idealab.tools" },
        { name: "Johnny Sovacool", url: "https://johnsovacool.idealab.tools" }
	];
</script>

<div class="px-10 py-10 max-w-3xl mx-auto">
    <p class="text-gray-800 text-center">In the IdeaLab this quarter 6th Grade went through the whole process of planning, designing, and building a website that features something they are passionate about. Below are the websites they built and are best viewed on a desktop.</p>
    <p class="text-gray-600 text-center text-sm pt-6">** Some websites may not be fully functional on a mobile device. **</p>
</div>
<div class="grid grid-cols-2 lg:grid-cols-4 gap-6 px-10 py-10">
	{#each students as student}
		<a 
			href={student.url} 
			target="_blank" 
			rel="noopener noreferrer"
			class="p-6 bg-white aspect-square flex items-center justify-center rounded-lg shadow-md hover:shadow-lg transition-shadow duration-200 border border-gray-200 hover:border-blue-300"
		>
			<h3 class="text-lg font-semibold text-gray-800 text-center">
				{student.name}
			</h3>
		</a>
	{/each}
</div>