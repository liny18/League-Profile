<script>
</script>

<div class="nav-wrapper flex justify-between items-center bg-orange-500 p-5">
	<a href="#" class="brand-logo">
		<img src="/l-black.png" alt="logo" class="logo rounded-md" width="50" height="50" />
	</a>
	<form class="input-field flex justify-between items-center rounded-2xl bg-gray-50 text-gray-900">
		<select name="region" class="bg-gray-800 text-white rounded-md p-1 ml-4 cursor-pointer">
			<option value="na1">NA</option>
			<option value="euw1">EUW</option>
			<option value="eun1">EUNE</option>
			<option value="kr">KR</option>
			<option value="oc1">OCE</option>
			<option value="br1">BR</option>
			<option value="jp1">JP</option>
			<option value="la1">LAN</option>
			<option value="la2">LAS</option>
			<option value="ru">RU</option>
			<option value="tr1">TR</option>
		</select>
		<input
			class="bg-transparent w-full p-3 rounded-2xl mr-2 outline-0"
			id="search"
			type="search"
			placeholder="Summoner name"
			required
		/>
		<label
			class="label-icon bg-orange-400 hover:bg-orange-600 cursor-pointer px-4 py-5 rounded-r-2xl"
			for="search"
		>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				class="icon icon-tabler icon-tabler-search"
				width="24"
				height="24"
				viewBox="0 0 24 24"
				stroke-width="2"
				stroke="currentColor"
				fill="none"
				stroke-linecap="round"
				stroke-linejoin="round"
			>
				<path stroke="none" d="M0 0h24v24H0z" fill="none" />
				<path d="M10 10m-7 0a7 7 0 1 0 14 0a7 7 0 1 0 -14 0" />
				<path d="M21 21l-6 -6" />
			</svg>
		</label>
	</form>
	<div />
</div>
