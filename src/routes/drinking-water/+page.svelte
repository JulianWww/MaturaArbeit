<script>
    import TopBar from "../TopBar.svelte";
    import Card, {Content} from "@smui/card";
</script>

<TopBar prev={true}/>
<main>
    <Card>
        <Content>
            <h1>Trinkwasser</h1>
        </Content>
        <div class="divider"/>
        <Content>
            Lorem impsum
        </Content>
    </Card>
</main>