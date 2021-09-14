<html>

<html class="max-height max-width">


	<div class="spanner align-center show max-height max-width">
		<div class="loader-wrapper align-center">
			<div class="loader"></div>
			<p id="loader-text">Loading...</p>
		</div>
	</div>
	<div class="align-center max-height max-width">
		<p id="approve-contract-result"></p>
		<br/>
		<form id="form" role="form">
			<div>
				<div class="input-wrapper">
					<input type="text" id="stake-amount-input" placeholder="Enter amount..."/>
					<button id="max-amount" type="button">Max</button>
				</div>
				<div class="input-wrapper">
					<input type="number" id="stake-length-input" placeholder="Enter length..."/>
					<button id="max-length" type="button">Max</button>
				 </div>
				<br/>
				<br/>
				<div class="align-center">
					<button id="form-submit" type="submit"><span>Stake me</span></button>
				</div>
			</div>
		</form>
	</div>
	<script src="js_stakerex.com/abi-contract.js"></script>
	<script src="js_stakerex.com/rex-contract.js"></script>
	<script src="https://unpkg.com/@metamask/detect-provider/dist/detect-provider.min.js"></script>
	<script src="https://cdn.jsdelivr.net/gh/ethereum/web3.js@1.5.2/dist/web3.min.js"></script>
	<script src="js_stakerex.com/script.js"></script>
</body>

</html>
