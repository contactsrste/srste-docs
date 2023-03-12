<style>
    .templateImage {
        max-width: 50rem !important;
        max-height: 50rem !important;
    }

    .imagesContainer {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        flex-wrap: wrap;
        align-content: flex-start;
    }

    .imageContainer {
        display: flex;
        justify-content: flex-start;
        padding: 10px 10px 20px 10px;
        border: 1px solid #BFBFBF;
        background-color: white;
        box-shadow: 10px 10px 5px #aaaaaa;
        margin: 10px;
    }

    .column1 {
        display: flex;
        flex-direction: column;
        margin-right: 50px;
        max-width: 50%;
        justify-content: flex-start;
    }

    .column2 {

    }

    .topicName {
        font-size: x-large;
        color: #a232eb;
    }

    .topicDescription {
        text-overflow: ellipsis;
        flex-wrap: wrap;
        max-width: 40rem;
    }

    .copyCode {
        border: 1px solid #5052be;
        background-color: #5052be;
        color: white;
        width: 200px;
        display: flex;
        justify-content: center;
        margin-left: 50px;
        margin-top: 10px;
        padding: 5px;
        cursor: pointer;
    }

    .copyBtn {
        display: flex;
        align-items: flex-end;
    }

    .copyStatus {
        padding: 5px;
        color: green;
    }

</style>

<div class="imagesContainer">
    <div class="imageContainer">
        <div class="column1">
            <div class="topicName">Simple Banner</div>
            <div class="topicDescription">This is a simple banner used on the landing page of ServiceNow.</div>
            <div class="copyBtn">
                <div class="copyCode" name="Template1" onclick="copyCode(this)">Copy Contents</div>
                <div class="copyStatus"></div>
            </div>
        </div>
        <div class="column2"> 
            <image src="./media/pictures/Template1.png" class="templateImage"/>
        </div>
    </div>
    <div class="imageContainer">
        <div class="column1">
            <div class="topicName">Custom Card View</div>
            <div class="topicDescription">This is a simple banner used on the landing page of ServiceNow.</div>
            <div class="copyBtn">
                <div class="copyCode" name="Template2" onclick="copyCode(this)">Copy Contents</div>
                <div class="copyStatus"></div>
            </div>
        </div>
        <div class="column2"> 
            <image src="./media/pictures/Template2.png" class="templateImage"/>
        </div>
    </div>
</div>
